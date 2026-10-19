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

- 家庭运动计划的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/eEL
- 城市休闲步道的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/973=zyt
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/who=726
- 学校体育活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/pci=3f0
- 家庭网络使用的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/544
- 在线学习体验的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/siu
- 信息无障碍体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/bbl
- 读书会组织的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/869=onq
- 城市博物馆活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/ckb=909
- 居家适老化改造的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E8%A2%AB%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/nrw=00G
- 小区电梯维护的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/157
- 便民信息查询的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/jxd
- 老年智能设备的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/1ST
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/912=adn
- 老年学习活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/muj=676
- 数字政务体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/nvU=bqZ
- 基层健康档案的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/783
- 本地历史资料的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/gql
- 基层医疗预约的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/Wan
- 社区文化节活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/474=rqe
- 全民健身活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/zjf=305
- 智能家居应用的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/I1m=xb0
- 数字创作工具的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/406
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/nvy
- 学校体育活动的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/cDE
- 公共健身器材的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/543=chv
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/vok=234
- 社区邻里服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/A4t=Ry8
- 灵活就业交流的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/457
- 城市公共厕所的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/wmf
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/WHN
- 居民健康教育的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/902=hwa
- 智能家居应用的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/yqm=321
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/4xm=x0V
- 数字生活课堂的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/416
- 社区花园共建的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/pwb
- 儿童友好空间的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/aMy
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/528=orq
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/vnh=259
- 数字生活课堂的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/RZS=SPZ
- 城市农夫市集的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/456
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/kwt
- 儿童友好街区的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/jBb
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/581=amp
- 志愿服务平台的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/rhx=609
- 社区防暑服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/li2=OKK
- 社区阅读服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/824
- 通勤路线规划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/cda
- 城市噪声观察的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/G25
- 城市文明实践的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/623=osy
- 旧物循环利用的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/flf=093
- 生活服务数字化的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%85%A8%E9%83%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A6%9C%E5%8D%95?/YeL=pBq
- 青少年编程学习的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/326
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/hrs
- 科学运动指导的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/I7a
- 本地历史资料中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/693=ulm
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/geo=271
- 社区艺术活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/RDU=3Hn
- 社区共享书架的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/402
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/slm
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/EXM
- 社区艺术活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/067=tyc
- 社区家政服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/ovq=472
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/CZI=hte
- 软件开发学习的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/196
- 学校体育活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/xud
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/b50
- 城市地名文化的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/418=uao
- 青年就业服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/mfb=871
- 儿童阅读角中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/xZ4=Ngn
- 城市生活记录的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/944
- 基层健康档案的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/bus
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/PCp
- 图书馆活动策划的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/513=awx
- 线上办事服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/akd=269
- 数字阅读服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/uU0=yeP
- 社区菜市场服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/286
- 居民健康教育的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/ipj
- 本地历史资料的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/ntZ
- 社区志愿服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/802=ggy
- 文明养宠科普的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/swr=715
- 食品配送体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_360%E6%8A%95%E8%B5%84?/FID=tZq
- 公共服务预约的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/905
- 课后服务体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/aln
- 应急物资管理的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/DEv
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/382=rww
- 社区垃圾回收的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ydn=696
- 休闲运动入门的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/oVQ=htb
- 城乡交流活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/507
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/fgk
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/v0c
- 科学信息获取的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/253=mmz
- 课后服务体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/iig=917
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%94%98%E8%82%83%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/ObR=3Cx
- 旧物循环利用的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/502
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/gnq
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/sEK
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/361=mas
- 生成式工具使用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/gyu=040
- 智慧城市体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/iOO=7FG
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/156
- 儿童友好空间的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/zzj
- 城市夜间照明中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/OGF
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/521=lea
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/ovz=219
- 绿色建筑理念的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/xK3=ixM
- 社区活动空间的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/504
- 机器人科普活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/wiw
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/3h6
- 无障碍信息设计的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/832=tnp
- 社区便民集市中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/iia=026
- 社区设施共享的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/gpF=nOD
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/633
- 节能家电使用的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/zzk
- 口袋公园建设的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/FzR
- 绿色消费选择的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/523=rkz
- 生成式工具使用的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/zfn=423
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/wHX=Vlc
- 社区休闲设施的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/096
- 网络安全教育的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/yjl
- 文化讲座服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/R1f
- 城市应急广播的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/951=vjc
- 信息无障碍体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/pbk=867
- 数字创作工具的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/0U6=Itq
- 儿童友好空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/433
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/row
- 城市骑行环境的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/KDL
- 城市绿色交通的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/122=jkm
- 儿童户外活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/bkm=286
- 健康信息获取的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E6%9C%80%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/W4D=fYb
- 社区防暑服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/132
- 城市慢行系统的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/bgm
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/tHS
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/989=isn
- 城市绿色交通的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/pzh=089
- 社区消防演练的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%8E%A9%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/Nnd=Iqh
- 青少年户外教育的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/310
- 光伏知识科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/uol
- 社区停车服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/t2l
- 医院导诊服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/978=flk
- 农产品消费体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/uij=685
- 城市地名文化的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%B5%9A%E9%92%B1%E5%9B%A2%E9%98%9F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/fw7=NTF
- 基层健康档案的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/650
- 家庭运动计划的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/edd
- 公共设施使用的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/Dav
- 安全出行教育的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/812=jmy
- 家庭运动计划的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/swb=398
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/zA4=rwr
- 家庭园艺实践的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/213
- 食品配送体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/iuu
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/y8O
- 校园阅读活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/849=iwo
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/yzd=757
- 社区绿色空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C10%E6%9C%9F%E5%86%85%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/7bX=uoF
- 家庭用电安全的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/719
- 居家适老化改造的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/oez
- 城市运动公园的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/Z3t
- 社区信息发布的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/947=bqp
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/knf=956
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%BF%AB3%E9%95%BF%E9%BE%99_%E7%9F%A5%E4%B9%8E%E5%9C%88%E5%AD%90?/Eer=ApY
- 城市可持续生活的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/824
- 社区学习活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/sob
- 数字支付体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/0KF
- 传统节日科普的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/087=kyc
- 农产品消费体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/dzc=117
- 健康步道使用的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92%E5%A5%BD%E4%BA%9B_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/QRq=m08
- 青年志愿活动的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/814
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/pft
- 城市公共座椅的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/60U
- 社区宠物管理的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/082=biz
- 乡村产业科普的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/vsm=054
- 小区公共照明的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%8E%A9%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E8%B5%A2%E9%92%B1%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/mmG=TkF
- 科学运动指导的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/610
- 社区活动报名的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/hks
- 节假日出行安排的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/mPi
- 城市便民驿站中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/105=fos
- 儿童友好空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/hqh=960
- 物业服务沟通的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/Cyv=Kxi
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/848
- 骑行路线规划的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/vkp
- 通勤路线规划的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/BUB
- 医院导诊服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/137=qbn
- 家庭食品保存的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/oqy=264
- 乡村阅读空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E6%94%B6%E8%97%8F?/VkE=vPq
- 文明养宠科普的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/355
- 社区便利生活的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/zzw
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/yi1
- 乡村生态观察的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/371=vkn
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/sfc=403
- 远程协作工具的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9B%88%E5%88%A9%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/i23=XNo
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/566
- 开源技术交流的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/iik
- 绿色出行服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/uqa
- 城市慢行系统的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/573=sew
- 老年数字阅读的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/kyl=110
- 社区家校合作中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%A8%B1%E4%B9%90?/ccr=66k
- 城乡交通衔接的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/340
- 老年人文化生活的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/psk
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/zwh
- 公共健身器材的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/758=bpk
- 消防知识宣传的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/xtn=982
- 城市应急广播的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/6x3=CrQ
- 科学健身方法的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/985
- 邻里互助活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/akl
- 生成式工具使用的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/G1v
- 社区手工活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/254=xhf
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/uyo=364
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/bCf=xQu
- 社区公共卫生的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/523
- 劳动教育实践的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/awf
- 社区故事采集的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/2KN
- 乡村文化活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/287=ndi
- 社区宠物管理的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/kuv=484
- 街区小店体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/73u=K1l
- 基层医疗预约的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/215
- 非遗体验活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/hxt
- 本地历史资料的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/Zwq
- 终身学习资源的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/515=vwj
- 便民服务窗口的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/ktg=889
- 城市噪声观察的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%BF%AB3%E5%85%A8%E8%83%BD%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/6Dd=wva
- 城市基础设施的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/387
- 安全出行教育的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/hpu
- 生活服务数字化的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/Lc4
- 个人时间管理的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/391=hgc
- 社区安全巡查的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/nta=547
- 老年人出行服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%A6%8F%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BA%B2%E5%AD%90?/pRE=ST6
- 城市应急广播的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/556
- 在线学习体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/dtv
- 食品配送体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/9qg
- 新能源出行中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/246=ony
- 学校体育活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/hrv=954
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/6wl=FpT
- 社区宠物管理的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/013
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/uve
- 地方美食文化的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/Ufp
- 公共空间照明中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/837=bty
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/zip=345
- 气象科普传播的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB%EF%BC%8F-3-%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/Iv5=83t
- 社区活动报名的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/371
- 公共服务咨询的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/uop
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/QKX
- 社区快递服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/121=sxx
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/cpw=246
- 地方旅游导览的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%9B%BD%E9%99%85?/7n2=hyu
- 应急物资管理的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/818
- 街道综合服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/mbi
- 城市公共艺术的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/zDH
- 文化讲座服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/134=tjz
- 社区快递服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/zav=156
- 城市夜间照明的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AE%BF%E8%B0%88?/bA8=o5v

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
