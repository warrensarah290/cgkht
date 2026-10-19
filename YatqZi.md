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

- 社区共享书架的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/kin=578
- 新能源出行的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/1pB=m0y
- 乡村教育资源的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/975
- 社区教育资源的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/twq
- 家庭网络使用的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/xbd
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/526=auk
- 社区菜市场服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/dch=041
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/Mps=epN
- 智慧停车服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/670
- 应急物资管理的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/okc
- 数字艺术创作的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/yWi
- 社区教育资源的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/457=trx
- 城市树木认养的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/dwl=048
- 传统手工艺体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/vxB=S9T
- 市民意见收集的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/804
- 社区共享书架的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/klh
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/7at
- 基层健康服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/421=vhl
- 乡村生态观察的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/kxb=084
- 文化讲座服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_PC%E8%87%86%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/kHu=y3U
- 家庭用电安全的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/991
- 城市生活记录的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/awc
- 公园休闲体验的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/Nlf
- 地方文化传播的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/574=whq
- 家庭急救准备的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/qos=773
- 公共交通接驳的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/mAC=hYD
- 数字地图应用的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/522
- 课后服务体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/hgq
- 城市应急科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/PJl
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/245=vzy
- 城市文明出行的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/ycv=189
- 公共文化活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/qWa=FBq
- 周末休闲规划的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/829
- 乡村公共文化的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/ied
- 青少年科技社团的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/M81
- 物业服务沟通的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/561=oct
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/eky=393
- 数据分析入门的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/lau=yKs
- 社区便民服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/718
- 绿色出行服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/wxg
- 校园节能行动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/7im
- 社区养老服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/558=duf
- 校园阅读活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/vmw=455
- 社区志愿服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/ELR=Dj6
- 网络安全教育的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/260
- 社区绿色空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/afn
- 社区老年食堂的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/eMw
- 公园亲子设施的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/331=zcl
- 社区应急准备的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/kid=849
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/WrI=V0Y
- 青年职业探索的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/296
- 城市适老服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/sxb
- 公共空间照明的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/d2m
- 居家防滑改造的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/343=cdk
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/fet=695
- 地方民俗记录的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/Leg=elK
- 节假日出行安排的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/444
- 物业服务沟通的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/smt
- 小微企业服务的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/Put
- 老旧小区改造的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/439=vhr
- 电子商务服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/lnb=674
- 城市夜间生活的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/ZMs=RyN
- 数字档案服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/627
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/ndp
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/mtw
- 家庭节能实践的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/809=nen
- 青少年科技社团的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/cjj=207
- 文化讲座服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/TJK=isw
- 社区志愿服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/739
- 社区老年食堂的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/rsg
- 邻里共享空间的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/Zaa
- 城市博物馆活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/134=ucp
- 软件开发学习的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/tar=720
- 社区商业活力的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/rfF=Lwd
- 便民服务地图的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/841
- 公共服务数字化的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/spr
- 智慧停车服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/rx1
- 社区托育服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/856=sby
- 乡村产业科普的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/yzu=959
- 街区绿化养护中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/6S8=VWP
- 个人时间管理的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/838
- 公共空间照明的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/jyl
- 家庭消费规划的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/Ywl
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/618=ndu
- 城市慢行系统的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/iac=458
- 智能手机助老的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/YJJ=QgR
- 家庭消费规划的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/358
- 城市步行友好的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/njm
- 本地旅行体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/7Ir
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/933=haf
- 社区学习活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/eli=308
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/dIK=Edw
- 数字资源检索的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/079
- 社区体育组织中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/dxs
- 青少年户外教育的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/aQT
- 公共服务评价的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/993=glt
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/vuz=911
- 数字生活课堂的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/g2t=Z3V
- 个人数据管理的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/816
- 社区消防演练的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/cvr
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/4hZ
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/647=mcx
- 青年志愿活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/fnw=994
- 城市便民驿站的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/4Zg=f2f
- 无障碍信息设计的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/633
- 社区知识分享的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/sgi
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/gZZ
- 家庭健康管理中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/376=vrl
- 跨代沟通活动的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/cnm=146
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/18a=58D
- 城市展览体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/567
- 城市噪声观察的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/mty
- 社区修缮行动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/pYA
- 社区宠物管理的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/041=kse
- 传统手工艺体验的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/tau=758
- 街区小店体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/mtg=pqC
- 社区环保活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/961
- 数字便民地图的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/cbc
- 食品安全科普的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/IAM
- 传统节日科普的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/220=fcf
- 便民维修服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/why=064
- 青少年科技社团的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F28%E6%98%AF%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%90%97_36%E6%B0%AA%E9%97%AE%E7%AD%94?/85t=qzM
- 社区托育服务的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/108
- 社区邻里服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/yuo
- 街区更新实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/Zib
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/256=vhf
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/mdl=530
- 学校体育活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F28%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/9Wb=l49
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/240
- 新能源知识普及中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/vqt
- 城市生活服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/3y8
- 应急物资管理的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/845=pdd
- 科技馆参观体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/htu=613
- 本地消费场景的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F28%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85?/XDU=ttC
- 城市共享单车的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/573
- 家庭健康科普的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/bfl
- 数字资源检索的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/eev
- 智能家居应用的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/221=rps
- 药品使用科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/kpl=162
- 网络安全教育的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F28%E6%B0%B8%E4%B9%85%E8%B5%9A%E9%92%B1%E6%A8%A1%E5%BC%8F_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/yMW=Ntj
- 社区活动策划的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/495
- 城市微更新实践的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/vxb
- 老年学习活动的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/NLh
- 数字支付体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/909=bkb
- 社区快递服务的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/wos=044
- 家庭节能实践的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F28%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%94%BE?/wxk=rtq
- 城市文化路线的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/802
- 志愿者培训交流的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/cni
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/tNZ
- 居民健康教育的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/233=trf
- 居家适老化改造中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/hth=100
- 科学教育活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/kYz=KIw
- 城市应急科普的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/724
- 数字创意课程的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/vgx
- 非遗体验活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/TQv
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/136=yeu
- 青年职业探索中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/hpq=020
- 生成式工具使用的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%80%A5%E9%80%9F28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/zYU=ecs
- 社区信息发布的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/496
- 社区设施共享的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/dzc
- 城市休闲步道的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/ZBf
- 老年友好服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/921=pxt
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/zws=953
- 城市适老服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/kpI=UvG
- 节日文化体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/698
- 社区文化节活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/pgo
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/iZS
- 青少年科技社团的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/930=gop
- 生活技能分享的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ewl=336
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E9%A2%84%E6%B5%8B%E5%8F%82%E8%80%83_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/vom=aCq
- 公共服务预约的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/961
- 志愿者培训交流的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/mac
- 创业经验分享的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/xdI
- 气象科普传播的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/499=gsp
- 城市基础设施的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/yfg=826
- 无障碍信息设计的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F28_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/tT9=vNu
- 家庭照护支持的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/284
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/rmg
- 文化讲座服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/qJ2
- 居民健康教育的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/511=ymw
- 公共服务评价的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/nrj=323
- 校园安全教育的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/TOF=LHO
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/149
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/wds
- 社区绿色空间的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/piy
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/791=uno
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/zkj=428
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F28%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/0Fw=QZd
- 社区快递服务的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/152
- 软件开发学习的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/axh
- 基层医疗预约的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/JRM
- 公共服务数字化的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/993=jfy
- 社区防暑服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/btk=215
- 学校食育活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9Fpc%E9%A2%84%E6%B5%8B_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/JyH=UCy
- 物业服务沟通的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/551
- 网络信息辨识的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/xer
- 城市建设科普的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/Ege
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/303=eqk
- 基层健康档案的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/pns=016
- 青少年户外教育的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A5%9E%E4%B9%9028%E6%80%A5%E9%80%9F10%E6%A8%A1%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/nVd=gIe
- 文化讲座服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/530
- 街道综合服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/lji
- 乡村阅读活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/aeN
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/333=csy
- 电子商务服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/hji=845
- 社区设施共享的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F28%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/ylP=HWx
- 本地历史资料的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/008
- 生活垃圾回收的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/rnk
- 城市共享单车的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/HWt
- 城市绿色交通的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/600=kxv
- 社区活动空间的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/mpq=037
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/SjS=B2B
- 科普展览体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/808
- 数字生活课堂中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/qnv
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/CTz
- 智能家居应用的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/456=ubl
- 家庭科学教育的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/apm=669
- 绿色生活实践的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bpc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/BwF=Le1
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/560
- 城市公共厕所的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/tpt
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/FrK
- 职业技能学习的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/496=fvp
- 网络安全教育的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/kpe=251
- 社区消防演练的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/9eg=hiO
- 便民信息查询的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/514
- 公共服务咨询的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/xjt
- 户外活动组织的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/Hjd
- 健康步道使用的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/139=bny
- 公益活动组织的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/vix=885
- 公共服务指南的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%8628_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/D5H=Dnx
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/282
- 便民服务地图的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/myh
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/gF7
- 开放式学习空间的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/977=fer
- 社区活动空间的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/xjr=369
- 信息无障碍体验的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.0%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B100%25_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/R6P=6VP
- 数字公共文化的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/575
- 青年就业服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/ccx
- 社区艺术活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/B2x
- 急救知识普及的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/659=nve
- 农业科普体验的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/ezy=370
- 基层服务创新的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/gJO=CZA
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/953
- 便民维修服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/yuq
- 乡村公共服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/fkm
- 公共交通接驳的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/377=rhu
- 社区活动报名的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/rcu=674
- 家庭节能设备的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%862.0%E9%A2%84%E6%B5%8B%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/0m0=SyR
- 城市绿色交通的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E7%AE%97%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/605
- 老年人日常照护的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E7%AE%97%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/xub

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
