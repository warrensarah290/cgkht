# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 街区道路维护的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/276
- 城市公共饮水的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/nww
- 本地历史资料的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/WEG
- 安全出行教育的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/379=opp
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/smy=531
- 科学健身方法的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9500%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/i7c=gew
- 个人数据管理的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/005
- 公共服务预约的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/uqd
- 街区道路维护的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/gix
- 家庭节能设备的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/520=nre
- 街道综合服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/geo=107
- 安全出行教育的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9500~welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/AMH=HIQ
- 城市绿色交通的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/572
- 社区垃圾分类的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/nvd
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/O4U
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/254=wfa
- 社区宠物管理的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/obv=123
- 家庭饮食安排的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/qHk=auz
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/084
- 社区生活指南的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/tih
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/8es
- 公交站点体验的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/451=fjo
- 城市空气科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/coy=190
- 环境监测科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8~%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/Ecm=t3o
- 数字便民地图的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/245
- 开放数据应用的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/krp
- 社区文化节活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/BRj
- 数字资源检索的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/251=dkb
- 城市步行环境的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/zmv=275
- 个人数据管理的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/TvP=EjV
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/963
- 公共场馆服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/rnc
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/E46
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/878=hrk
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/neg=505
- 社区公共议事的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89?/BgT=OIA
- 社区家政服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/771
- 创业经验分享的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/hta
- 街区绿化养护的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/2CT
- 农产品品牌传播的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/269=xqn
- 乡村文化活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/cny=679
- 公共卫生宣传的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/PPi=qO7
- 青少年户外教育的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/036
- 社区知识分享的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/jls
- 社区互助网络的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Fsf
- 社区家政服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/390=sez
- 城市便民驿站的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/fjb=709
- 食品配送体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Oi7=5Gh
- 社区宠物管理的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/259
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/svm
- 食品安全科普的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/FWv
- 公共场馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/304=scg
- 儿童运动体验的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/yuw=365
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/ZQs=w3p
- 城市骑行环境的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/192
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/prc
- 社区便民服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/b3W
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/350=jju
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/jaj=739
- 职业技能学习的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/gmn=QhY
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/133
- 乡村公共服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/shw
- 乡村文化活动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/6Wa
- 数字生活课堂的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/933=slm
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/qou=638
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E9%9B%86%E5%9B%A2%E8%83%BD%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/A8o=kNa
- 乡村文化活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/498
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/zfp
- 便民服务窗口的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/EvF
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/367=byh
- 城市休闲步道的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/thm=177
- 老年人出行服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/ySI=js5
- 线上阅读资源的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/645
- 社区停车服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/qsx
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/3My
- 城市公共空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/885=ytu
- 农村环境治理的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/zce=873
- 节约用水实践的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/Egk=wb3
- 数字艺术创作中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/990
- 城市博物馆活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/lle
- 灵活就业交流中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/iSW
- 科学教育活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/856=ege
- 邻里互助活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/ekf=107
- 网络信息辨识的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/pG2=9gz
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/075
- 城市住房服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/qkn
- 乡村教育资源的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/3CA
- 环境监测科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/418=iuh
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/tft=785
- 运动安全知识的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/IEu=yvl
- 城市游园体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/439
- 公共空间休憩的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/wrf
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/6wj
- 社区共享书架的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/181=xoc
- 城市夜间照明的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/mya=585
- 公共交通接驳的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E?/ZbG=JII
- 家庭安全提示的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/130
- 社区学习活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iar
- 城市生活服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Xo9
- 城市步行友好的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/887=nea
- 校园节能行动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iny=323
- 基层健康服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/S6R=Vus
- 家庭教育交流的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/802
- 图书借阅体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/xdt
- 社区活动报名的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/j2o
- 小区停车协商的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/127=vda
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/fzi=058
- 城市应急广播的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8D%9A%E5%AE%A2?/VVv=XYk
- 儿童安全出行的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/608
- 基层健康服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/ctf
- 非遗体验活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/L6S
- 城市夜间生活的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/695=uwq
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/gam=949
- 青少年户外教育的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/r2p=PCz
- 城市慢行系统的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/990
- 便民服务窗口的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/hdw
- 老年友好服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/tVV
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/024=srj
- 绿色生活实践的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/asu=475
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/edZ=6YQ
- 青少年户外教育的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/742
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/obg
- 绿色消费选择的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/7CX
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/351=tzo
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/dbx=983
- 居民健康教育的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/vwJ=tX6
- 乡村文化空间的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/685
- 生活垃圾减量的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/psv
- 城乡公共服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ePT
- 城市步行友好的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/802=nzq
- 周末休闲规划中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/who=417
- 公共服务数字化的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/1PH=vbb
- 老年智能设备的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/822
- 城市应急科普的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/asd
- 节气饮食文化的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/g5C
- 数字设备回收的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/451=jql
- 社区花园共建中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/nvt=005
- 公共服务数字化的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/ZzH=boX
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/713
- 社区快递服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/tqx
- 骑行路线规划中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/eSZ
- 公共空间安全的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/448=nhp
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/pci=344
- 个人数据管理的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/n1f=X8O
- 便民服务地图的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/299
- 智慧城市体验的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/igv
- 传统节日科普的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/7F1
- 社区法律科普的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/087=lmv
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/pki=346
- 公共场所导视的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/MsK=Bty
- 公园休闲体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/589
- 老年人日常照护的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/gfy
- 节日文化体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/VvR
- 家庭环保行动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/014=jdh
- 城市可持续生活中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/jub=123
- 公共空间安全的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/P0A=8yh
- 儿童户外活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/926
- 城市社区治理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/dnx
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/l6P
- 社区便民集市的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/075=xjr
- 城市生活服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/wkx=637
- 开源技术交流的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%87%E5%AE%B6%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/g29=Jak
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/869
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/tlp
- 社区家校合作的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/eQh
- 网络安全教育的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/993=ykw
- 节能生活方式的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/bxt=825
- 公共设施使用的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8857_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/siR=gBT
- 绿色出行服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/746
- 公共服务咨询的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/ijo
- 公共设施使用的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/pP3
- 校园阅读活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/630=cgx
- 城市应急科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/qvs=375
- 青少年科技社团的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/MVk=5O7
- 社会体育指导的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/286
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/kqb
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/Gph
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/273=sqi
- 新能源知识普及的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/aia=504
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/FhU=1c7
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/316
- 机器人科普活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/zat
- 社区交通安全的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/gxC
- 公共服务评价的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/601=fab
- 急救知识普及的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/zaq=148
- 家庭环保行动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_857%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8appl%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/dJI=Jso
- 健康步道使用的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/265
- 文化场馆预约的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/pxz
- 城市慢行系统的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/Kuw
- 家庭用电安全的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/889=hmn
- 数字素养提升的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/nwr=448
- 城乡交流活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_656%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/Y8d=g2B
- 基层服务创新的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/427
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/cal
- 创业经验分享的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/7D3
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/108=ifd
- 乡村公共文化中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/sgf=498
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_22%E5%BD%A9%E4%B8%8B%E8%BD%BD878%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A7%91%E6%8A%80?/I30=HIO
- 社区安全巡查的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/005
- 社区故事采集的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/hxu
- 健康信息获取的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/kVy
- 社区环保活动的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/657=bia
- 城市公共自行车的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/wml=580
- 数字政务体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%893%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/AcR=nns
- 城市应急广播的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/943
- 跨代沟通活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/frw
- 居民健康教育的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/iI3
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/772=ycc
- 社区设施共享的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/rbi=221
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_857%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/9tG=skn
- 城市微更新实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/744
- 家庭阅读计划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ivi
- 通勤路线规划的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/Nel
- 城乡公共服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/984=pqs
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/lvl=286
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%B9%85%E4%B9%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/HxB=RBC
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/755
- 家庭理财科普的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/wrd
- 职业技能学习中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/5a0
- 街区更新实践的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/808=cor
- 公共交通接驳的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/abg=650
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_857%E5%BD%A9%E7%A5%A8-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/VNq=knB
- 家庭阅读计划的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/981
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/oho
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/Hh3
- 地方文化传播的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/958=ogj
- 社区学习活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/vbv=231
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/uhi=2wi
- 城市休闲步道的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/637
- 机器人科普活动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/gfl
- 物业服务沟通的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/zNi
- 社区设施共享的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/894=uyl
- 电子商务服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/dvl=945
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/ZMk=5he
- 社区心理支持的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/618
- 食品配送体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/ulk
- 全民健身活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/WQe
- 便民服务地图的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/150=ewo
- 口袋公园建设的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/fvn=698
- 城市公共艺术的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_857%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/PrH=teU
- 居民健康教育中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/210
- 电动汽车充电中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/frw
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/rT6
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/612=lul
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/mua=195
- 学校体育活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA%E6%97%A7%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/IOQ=MoB
- 农贸市场环境的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/059
- 学校体育活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/nuz
- 社区花园共建的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/u62
- 周末休闲规划的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/950=tjd

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
