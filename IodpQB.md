# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/054
- 家庭教育交流的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/yjv
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/4y5
- 生活垃圾回收的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/151=sqg
- 物业服务沟通的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/llj=862
- 物业服务沟通中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/iD2=6pD
- 城市公共空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/475
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/nnz
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/HNX
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/579=adj
- 线上办事服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/iuo=631
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%A7%91%E6%99%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BC%80%E5%A5%96%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/8DN=xXU
- 乡村生活观察的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/568
- 个人时间管理的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/fdu
- 志愿服务平台的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/SKS
- 家庭网络使用的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/665=aip
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/zjy=266
- 城市文明实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93--%E5%BC%80%E5%A5%96%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/CP1=85k
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/650
- 家庭急救准备的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/leo
- 电子商务服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/MLm
- 智能家居应用的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/166=ehd
- 老年人日常照护的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/did=477
- 课后服务体验的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%A2%91%E9%81%93--%E5%8E%86%E5%8F%B2%E6%95%B0%E6%8D%AE%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/POc=rxp
- 家庭消费规划的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/973
- 数字创意课程的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/dyj
- 生活垃圾减量的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/h5R
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/733=yvn
- 城市运动公园的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/mgb=506
- 骑行路线规划的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E6%9F%A5%E8%AF%A2--%E5%8E%86%E5%8F%B2%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/xLw=bGb
- 社区学习活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/392
- 社区宠物管理的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/hku
- 公共空间安全的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/wOA
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/159=vob
- 环境教育课程的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/oct=218
- 公共服务沟通的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2--%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/Bd9=YKx
- 公共空间休憩的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/038
- 数字学习资源的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/vzw
- 城市文明出行中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/J1O
- 街区绿化养护的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/224=zse
- 基层服务创新的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/vem=788
- 社区便民集市的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2--%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/dj8=Rlw
- 儿童友好空间的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/543
- 城市可持续生活的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/yhb
- 公共服务预约的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/Us7
- 家庭网络使用的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/246=wns
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/tso=379
- 城市休闲步道的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/IUa=2iY
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/925
- 校园节能行动的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/miz
- 社区活动空间的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/8WB
- 节能生活方式的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/795=ptr
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/lql=517
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2--%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/5d8=wWB
- 社区安全巡查的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/193
- 数字生活课堂的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/pie
- 环境教育课程的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/Bk7
- 公共卫生宣传的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/762=wuy
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/yfs=653
- 城市骑行环境的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95--%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/uyM=TzK
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/228
- 城乡交通衔接的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/yyl
- 数字档案服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/ijU
- 数字设备回收的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/767=jev
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/ybs=207
- 科学运动指导的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90--%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/Exq=HAp
- 乡村产业科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/804
- 智慧停车服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/qzg
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/4Hz
- 骑行路线规划中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/656=sww
- 社区设施共享的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/pop=111
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8--%E7%94%A8%E6%88%B7%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/Jt9=nkf
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/556
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/dke
- 社区宠物管理中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/vCP
- 科学观察活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/568=yrx
- 社区活动空间的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/csv=345
- 社区科普课堂的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8--%E5%9C%A8%E7%BA%BF%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/vv0=Kkl
- 终身学习资源的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/800
- 数字创意课程的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/wkg
- 城市空气科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/NsT
- 传统节日科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/309=bee
- 公共空间休憩的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/pwz=909
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%B5%84%E6%96%99%E6%9F%A5%E8%AF%A2--%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/U9n=CFl
- 老年人出行服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/348
- 公共服务沟通的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/fqt
- 社区读书角建设的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/XzL
- 社区学习活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/322=ehh
- 城市雨天出行的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/zdb=871
- 绿色生活实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/0Ui=Tyb
- 校园社团活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/550
- 社区便民集市中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/fok
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/rkM
- 线上阅读资源的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/179=vue
- 信息无障碍体验的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/irg=749
- 公共卫生设施的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/9UN=cUh
- 城市基础设施的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/650
- 居家防滑改造的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/cwy
- 无障碍出行的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/SGF
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/239=ksk
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/vkq=018
- 家庭阅读计划的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/vkR=kVz
- 城市绿色交通的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/535
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/smt
- 公益活动组织的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/xvy
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/655=jsm
- 机器人科普活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/mwy=571
- 生成式工具使用的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0--%E7%A7%BB%E5%8A%A8%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/Ykx=E3n
- 家庭饮食安排的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/608
- 公共图书馆服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/tjt
- 软件开发学习的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/ClD
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/827=gph
- 社区协商议事的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/moo=057
- 在线教育体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%B9%B3%C2%B7%E5%8F%B0--%E6%89%8B%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/YN1=7rv
- 社区生活指南的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/841
- 城市绿道建设的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/xxr
- 社区绿色空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/IQv
- 科技馆参观体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/905=ewx
- 城市展览体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/apd=060
- 社区阅读服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E9%97%A8%E6%88%B7--%E7%A7%BB%E5%8A%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/6ca=nlf
- 网络信息辨识的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/409
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/aaw
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/ogP
- 乡村阅读空间的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/464=xug
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/dxc=409
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E9%97%A8%E6%88%B7--%E6%89%8B%E6%9C%BA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/fcL=qOa
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/296
- 课后服务体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/wtw
- 青少年编程学习的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/Chh
- 社区科普课堂的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/183=ujy
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/pzq=396
- 职业技能学习的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E9%97%A8%E6%88%B7--%E5%BE%AE%E4%BF%A1%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/inS=hTp
- 城市生活服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/831
- 城市公共厕所的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/blo
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/LD0
- 健康饮食教育的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/364=xbu
- 社区共享书架的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/jsj=152
- 校园安全教育的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%9F%A5%E8%AF%86%E5%B9%B3%C2%B7%E5%8F%B0--%E5%BE%AE%E4%BF%A1%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/9Lb=Zoo
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/636
- 网络信息辨识的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/rtj
- 科学教育活动的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/Hlr
- 居民健康教育的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/958=wxp
- 科学信息获取的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/umg=940
- 环境教育课程的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%85%AC%E7%9B%8A%E5%B9%B3%C2%B7%E5%8F%B0--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/7QN=OTQ
- 社区交通安全的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/617
- 应急物资管理的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/baa
- 家庭运动计划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/fMa
- 居家适老化改造的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/417=gkn
- 食品安全科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/usu=473
- 数字生活课堂的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E8%A1%8C%E4%B8%9A%E5%AA%92%E4%BD%93--%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/kaa=a1o
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/831
- 数字生活课堂中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/rgs
- 公共服务咨询的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/orY
- 城市人文观察的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/849=aer
- 机器学习入门的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/fdm=027
- 环境教育课程的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E8%B5%84%E8%AE%AF--%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/8b7=JG2
- 社区文化传播的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/601
- 环境教育课程的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/pvx
- 青少年编程学习的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/8bg
- 儿童安全出行的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/962=pjs
- 智慧停车服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/kbq=214
- 周末休闲规划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%8E%A9%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/CEF=XFi
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/346
- 社区健康讲座的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/qft
- 社区阅读服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/Z4H
- 公共交通信息服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/605=chp
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/bgk=272
- 城乡公共服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/luD=aTV
- 数字学习资源的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/746
- 城市农夫市集的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/efw
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/Mxp
- 小区停车协商的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/566=gmx
- 公共空间安全的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/iod=327
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/h0N=QYz
- 社区志愿服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/087
- 科学健身方法的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/wdf
- 在线学习体验的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/vpf
- 家庭节能设备中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/973=oio
- 骑行路线规划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/ugy=108
- 社区教育资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/arI=LGb
- 社区宠物管理的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/498
- 家庭节能实践的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/ync
- 社区运动空间的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/EMg
- 公共设施维护中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/760=cov
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/ujh=626
- 城市文明实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/IdB=sSm
- 本地旅行体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/356
- 全民健身活动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/poc
- 日常摄影记录的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/pUg
- 小微企业服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/540=jmt
- 家庭急救准备的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/htg=400
- 科学观察活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/LnS=zIP
- 城市步行环境的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/017
- 社区教育资源的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/gwl
- 老年运动活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/ITr
- 软件开发学习的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/958=zsf
- 科学健身方法的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/fzf=362
- 老旧小区改造的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91IOS_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/sW9=M6I
- 急救知识普及的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/044
- 社区生活指南的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/viq
- 家庭消费规划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/fvi
- 学校食育活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/332=tai
- 科学健身方法的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/whz=364
- 社区活动策划的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/sMT=P8Y
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/100
- 邻里互助活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/ucs
- 社区养老服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/8Vf
- 数字创意课程的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/006=usd
- 校园阅读活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/irv=867
- 公共文化活动中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/Uwy=xzH
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/851
- 青少年户外教育的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/lfj
- 科学观察活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/Xmf
- 社区法律科普的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/227=asd
- 校园安全教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/qia=432
- 社区生活指南的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/8UT=7Ls
- 课后服务体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/858
- 校园阅读活动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/vuw
- 开放数据应用的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/SoW
- 数字公共文化的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/226=pob
- 生活垃圾回收的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/zxx=307
- 科学教育活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/lbj=cMj
- 农村环境治理的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/613
- 家庭园艺实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/kgp
- 社区家政服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/79b
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/013=hhf
- 绿色办公实践的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/krf=580
- 公共服务沟通的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/CZm=GPV
- 数据分析入门的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/380
- 科学教育活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/btg
- 健康饮水科普的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/Tm0
- 乡村教育资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/086=tbz
- 数据分析入门的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/sxr=460
- 社区设施共享的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/HYz=1yl
- 本地历史资料的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/924
- 数字支付体验的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/jfd
- 城市夜间照明的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/Qng
- 家庭环保行动的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/389=xve
- 城市基础设施的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/xqx=639
- 社区信息发布的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2?/qWW=TvT
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/303
- 城市基础设施的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gos
- 公共服务预约的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/6Q0
- 社区公共卫生的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/383=sjz
- 社区读书角建设中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oga=561
- 本地消费场景的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%85%A8%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0Tq=WVB
- 数字设备回收的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0...%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/598
- 家庭防灾准备的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0...%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/qmr
- 市民意见收集的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0...%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/hOA
- 地方文化传播的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0...%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/643=ljf

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
