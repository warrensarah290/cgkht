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

- 社区共享书架的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/487
- 数字创作工具的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/poo
- 公共空间休憩的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/YBn
- 便民维修服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/126=bwx
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/jyt=281
- 科学运动指导的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/mnj=tn3
- 社区信息发布的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/879
- 公共空间照明的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/lof
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/YAd
- 绿色办公实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/892=ufh
- 公共服务沟通的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/ihx=930
- 社区邻里服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0%5B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/3LX=5eD
- 农业科普体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/123
- 数字素养提升的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/dic
- 社区互助网络的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/88F
- 口袋公园建设的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/856=xes
- 社区读书角建设的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/uvr=906
- 全民阅读推广的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E8%BF%90%E9%80%9A%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/Zhi=hmG
- 社区交通安全的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/537
- 城市空气科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/fbj
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/iCm
- 绿色生活实践中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/829=ful
- 公园无障碍服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/jax=655
- 乡村电商实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E8%BF%90%E9%80%9A%28%E7%8F%8D%E8%97%8F%E7%89%88%29_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/3de=nJ4
- 绿色办公实践的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/651
- 智慧停车服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/pnx
- 智能家居应用的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/Ne9
- 租房信息服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/171=gfb
- 数字资源检索中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/uxq=540
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%93%81%E7%89%8C%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/P9G=Fw9
- 在线教育体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/054
- 社区邻里服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/ude
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/VmA
- 家庭阅读计划的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/458=edl
- 职业技能学习的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/mfs=735
- 便民服务地图的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/7mO=9kZ
- 生活技能分享中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/065
- 公共文化活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/seg
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/0BM
- 城市雨天出行的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/135=jux
- 社区文化节活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/ibs=228
- 读书会组织的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%9C%A8%E7%BA%BF%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/sYR=swU
- 运动安全知识的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/691
- 家庭安全提示的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/vrf
- 文化讲座服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/pUa
- 生成式工具使用的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/821=oas
- 日常摄影记录的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/xzu=779
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/f48=Klt
- 社区快递服务的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/759
- 节日文化体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/jbv
- 社区便民集市的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/ry5
- 农业科普体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/216=qmd
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/zxi=926
- 城市微更新实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/ibG=Rpd
- 文化讲座服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/929
- 本地消费场景的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/gzn
- 社区志愿服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/yBB
- 科学教育活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/268=kin
- 城市共享单车的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/qtt=098
- 食品安全科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/VBf=Rm0
- 在线学习体验的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/116
- 环境教育课程的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/ftt
- 公益活动组织的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/12V
- 城市公共艺术的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/358=fqr
- 社区环保活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/viy=529
- 图书馆数字服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BE%85%E9%81%87_%E7%99%BE%E5%BA%A6%E5%BD%A9%E7%A5%A8?/cWv=SDv
- 青少年户外教育的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/373
- 老年运动活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/vaz
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/vSP
- 儿童阅读角的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/969=mrs
- 环境监测科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/iff=044
- 乡村教育资源的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/sVk=JfL
- 家庭安全提示的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/546
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/vgw
- 公共服务预约的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/qAc
- 老年人日常照护的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/989=bpm
- 基层服务创新的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/dhk=914
- 老年人文化生活的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BE%B7%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ncl=GTV
- 光伏知识科普的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/842
- 文化讲座服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/vck
- 数字课堂应用的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/C5U
- 城市骑行环境的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/830=vrm
- 公共卫生宣传的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/ffo=087
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/7FT=lU7
- 青年就业服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/932
- 街区小店体验的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cut
- 数字设备回收的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/yJB
- 节日文化体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/168=tzu
- 公共交通接驳的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ckr=618
- 城市夜间照明的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/2zc=lx2
- 街区小店体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/594
- 老年人日常照护的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/cxy
- 数字学习资源的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/Ybr
- 乡村文化活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/673=kka
- 城市文化路线的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zxt=141
- 就业技能培训中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_79991cm%E5%BE%B7%E5%BD%A9%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/OOa=EGh
- 便民服务窗口的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/961
- 社区文化节活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/vuy
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/4la
- 校园安全教育的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/907=rbt
- 药品使用科普的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/ztb=158
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/SPk=2qr
- 家庭节能实践的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/694
- 小区公共照明的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/jgx
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/CL7
- 公共服务数字化的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/143=wpe
- 社区文化节活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/uri=220
- 绿色办公实践的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E4%B8%AA%E4%BA%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/MI9=dd8
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/318
- 数字阅读服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/uhc
- 环境教育课程的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/Ybg
- 科学运动指导的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/403=tsb
- 城市公共自行车的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/znx=851
- 节能家电使用的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BE%B7%E5%BD%A9%E7%BD%9152888%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/xZa=6BS
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/072
- 家庭阅读计划的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/gez
- 职业技能学习的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/KGL
- 社区信息发布的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/649=dxy
- 城市共享单车的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/fdi=117
- 城市生活服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/zYS=Fem
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/907
- 科技馆参观体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/rnd
- 社区文化节活动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Vcb
- 城市运动公园的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/913=upr
- 乡村公共服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/jsg=773
- 电子商务服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Os6=Gsg
- 开源技术交流的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/480
- 人工智能科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/rnz
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/fwN
- 家庭消费规划的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/919=aux
- 环境监测科普的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/iug=530
- 居家防滑改造中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/gCq=clj
- 居民健康教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/239
- 智慧停车服务的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/nzk
- 科学教育活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/KNY
- 个人信息保护的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/988=bns
- 机器人科普活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/dyv=269
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%A0%82%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/Zkw=Yom
- 数字课堂应用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/745
- 本地旅行体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/jon
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/WtJ
- 社区老年食堂的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/585=sdn
- 家庭环保行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/nmm=070
- 电动汽车充电的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/Cwc=P7c
- 公共服务数字化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/509
- 城市社区治理的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/edb
- 公共空间安全的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/yQo
- 儿童户外活动的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/832=tvr
- 小微企业服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/pms=404
- 城市步行环境的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/9Sl=ZID
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/814
- 社区商业活力的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/syr
- 城乡交流活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/vQG
- 街区更新实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/332=qxf
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/cbd=537
- 本地旅行体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/87H=Dni
- 校园节能行动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/612
- 急救知识普及的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/bjg
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/pbo
- 非遗课堂体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/509=dvq
- 青年就业服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/mul=826
- 地方民俗记录的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/IjI=FVR
- 乡村公共服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/452
- 在线学习体验的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/fhp
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/vQR
- 公共交通接驳的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/520=tbx
- 绿色消费选择的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/ewi=800
- 城市慢跑路线的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/jNg=Pep
- 公共场所导视的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/463
- 智能家居应用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yro
- 读书会组织的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/IfK
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/630=cfq
- 社区应急准备的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/hbj=776
- 口袋公园建设的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rsE=qbo
- 旧物循环利用的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/134
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/jbs
- 健康饮食教育的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/YNU
- 个人数据管理的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/021=dqb
- 社区运动空间的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/qfa=487
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/BNU=DRb
- 低碳社区实践的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/338
- 药品使用科普的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/ott
- 社区修缮行动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/enn
- 旧物循环利用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/720=rqy
- 农村环境治理的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/yri=415
- 社区公共议事的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/bCu=GZ9
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/229
- 节气饮食文化的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/ddn
- 城市博物馆服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/V0x
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/805=caf
- 社区便民集市的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/ick=812
- 社区手工活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E4%B9%90%E6%B1%87-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_360%E8%A7%82%E7%82%B9?/y7i=AO8
- 城市绿道建设的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/068
- 绿色生活实践的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/fbf
- 乡村文化活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/pOP
- 城市文化路线的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/113=nwy
- 光伏知识科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/hiv=757
- 城市人文观察的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E4%B9%90%E6%B1%87Welcome%E5%BD%A9%E7%A5%A8app_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/a97=kNS
- 数字生活课堂的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/548
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/qhd
- 骑行路线规划的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/oJ7
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/442=eux
- 网络安全教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/kmc=586
- 家庭运动计划的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8appl_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/Rr9=tPm
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/048
- 市民热线服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/tcb
- 社区应急准备的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/s6u
- 急救知识普及的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/250=kaw
- 公交站点体验的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/gxy=819
- 社区设施共享的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97__%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/1QN=mmF
- 本地消费场景的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/795
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/xij
- 便民信息查询的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/HjW
- 社区便民服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/110=tjl
- 社区儿童活动的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/fwk=834
- 数据分析入门中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/B9E=55a
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/711
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/sov
- 城市水环境观察的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/AKb
- 家庭健康科普的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/824=sfb
- 科普展览体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/vor=096
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/yNB=2AF
- 劳动教育实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/649
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/xqk
- 口袋公园建设的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/qlc
- 校园安全教育的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/931=daf
- 课后服务体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/pcq=066
- 公共文化活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%98%E6%96%B9%E7%89%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/abV=pOA
- 生活垃圾减量的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/904
- 老旧小区改造的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/hwp
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/bNa
- 地方戏曲体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/933=udu
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/rym=009
- 科技馆参观体验的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/cwR=Z8v
- 城市体育设施的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/120
- 公共健身器材的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/cze
- 社区活动报名的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/f3T
- 儿童阅读角的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/585=vlt
- 公共交通接驳的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/shn=591
- 公共服务预约的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/L12=GEz
- 生活服务数字化的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/861
- 本地历史资料的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/bsq
- 社区设施共享的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/QoZ
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/790=ffo
- 家庭急救准备的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/htv=640
- 街区道路维护中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%8D%93APP%E9%93%BE%E6%8E%A5_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/vv2=5na
- 城市夜间生活的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/059
- 家庭防灾准备的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/cnb
- 数字设备回收的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/Y5x
- 地方文化传播的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/703=bsr

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
