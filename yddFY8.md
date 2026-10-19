# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 社区快递服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/APu
- 电子商务服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/140=bks
- 便民服务地图的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/edo=182
- 儿童友好空间的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/SGL=bCS
- 城市夜间照明的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/968
- 公共空间安全的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/ehn
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/JNb
- 城市住房服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/804=hus
- 智能手机助老的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/fku=612
- 家庭运动计划的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/qB5=oBz
- 社区家校合作的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/847
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/ycg
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/ZkR
- 城市空气科普的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/555=fwd
- 社区互助网络的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/wku=710
- 社区科普课堂的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/79P=3L1
- 公共设施使用的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/183
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/kfn
- 老年友好服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/0QA
- 城市基础设施的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/081=mmv
- 绿色办公实践的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/nzl=437
- 科普展览体验的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/uSB=mpi
- 城市文明出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/294
- 社区信息发布的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/xix
- 城市建设科普的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/BeA
- 软件开发学习中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/882=pgr
- 物业服务沟通的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/nhf=951
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/OVu=A68
- 数字素养提升的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/540
- 文明养宠科普中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/dsw
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/GDB
- 租房信息服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/501=pky
- 公共服务预约的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/eoi=566
- 城市公共艺术的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/E59=jFf
- 居家防滑改造的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/743
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/lvl
- 社区学习活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/dV5
- 社区防暑服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/103=utm
- 社区运动空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/nld=397
- 便民服务地图的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/5kK=Eu2
- 社区慢性病防控的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/216
- 科学观察活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/jgg
- 城市树木认养的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/cTV
- 城市空气科普的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/412=dnu
- 社区邻里服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/auk=974
- 科技馆参观体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/Mf7=HiT
- 传统节日科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/323
- 小区公共照明的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/ufp
- 青少年心理健康的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/xp3
- 健康饮食教育中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/707=vmu
- 城市展览体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/ion=157
- 智慧停车服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/sOU=a75
- 城市空气科普的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/345
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/wwh
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/v2X
- 健康饮水科普的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/378=znj
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/ynu=814
- 家庭用电安全的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/Ose=6uF
- 本地旅行体验的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/800
- 城市慢行系统的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/qmm
- 社区防暑服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/wOv
- 社区活动报名的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/232=tga
- 社区商业活力的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/tkg=194
- 图书馆数字服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/zk4=GeR
- 城市文化路线的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/920
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/bcu
- 社区共享书架的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/OKj
- 科学信息获取的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/195=dvq
- 街区小店体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/vnz=874
- 社区垃圾回收的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/3H4=Bwa
- 家庭安全提示的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/585
- 乡村产业科普的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/tmt
- 社区文化传播的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/O7c
- 小微企业服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/062=mth
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/obn=201
- 小区停车协商的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/EFB=0Jg
- 社区协商议事的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/787
- 城乡公共服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/pml
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/Kjg
- 社区交通安全的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/281=sqy
- 全民健身活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/zmb=179
- 城市博物馆活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%84%89%E8%84%89%E5%A4%B4%E6%9D%A1?/vYT=5e8
- 城市绿道建设的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/304
- 社区休闲设施中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/awl
- 新能源知识普及的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/NRR
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/607=hyq
- 城市步行友好的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/gvb=747
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/SMY=M19
- 公交站点体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/085
- 本地消费场景的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/msc
- 家庭用电安全的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/Jhj
- 科技馆参观体验的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/822=spn
- 公共服务评价的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/lyy=669
- 儿童友好空间的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/B9y=iSF
- 社区垃圾分类的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/771
- 个人时间管理的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/jzh
- 全民健身活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/TNq
- 公共服务咨询的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/638=ezo
- 传统节日科普的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/tcu=001
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E5%9B%BD%E9%99%85?/FI2=kCw
- 城市噪声观察的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/291
- 医院导诊服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/rxn
- 城市步行友好中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/uj5
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/714=jrb
- 城市体育设施的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/xtg=205
- 环境教育课程的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/DBA=wQQ
- 社区公共议事的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/999
- 家庭环保行动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/igs
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/WxR
- 社区绿色空间中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/779=hia
- 智能手机助老的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/oos=141
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/sna=s7L
- 社区商业活力的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/376
- 城市噪声观察的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/jda
- 青少年心理健康的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/yI6
- 社区教育资源的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/310=hii
- 家庭节能实践的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/icw=538
- 校园节能行动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_36%E6%B0%AA%E6%96%87%E5%8C%96?/zpa=mWb
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/333
- 急救知识普及的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/ctv
- 城市社区治理的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/EDH
- 家庭用电安全的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/143=dfw
- 安全出行教育的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/uhg=488
- 便民服务地图的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/Yqn=d2e
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/673
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/voe
- 城市适老服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/7Ek
- 节气饮食文化的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/266=lck
- 社区志愿服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/zdq=327
- 骑行路线规划的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/dIl=3Ap
- 开放式学习空间的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/956
- 数字支付体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/cem
- 公共服务数字化的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/ua0
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/642=mlq
- 社区协商议事的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/nmz=709
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E4%B9%B0%E5%85%A5%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/ns8=uSI
- 老年人出行服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/113
- 公共服务指南的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/dwj
- 数字学习资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/T7A
- 社区便民服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/008=zxc
- 城市社区治理的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/num=387
- 旧物循环利用的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E?/Q6o=ydc
- 休闲运动入门的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/313
- 本地旅行体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/wzp
- 本地消费场景的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/XMH
- 节假日出行安排的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/601=dcs
- 公园亲子设施中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/lvj=349
- 节约用水实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%94%E6%9C%9F%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%85%AC%E7%9B%8A?/cVu=tGd
- 学校体育活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/633
- 科学教育活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/jti
- 公共卫生设施的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/0rf
- 地方美食文化的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/581=jtw
- 儿童运动体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/yqt=322
- 城市公共空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/LLG=9fc
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/748
- 数字资源检索的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/jxp
- 公共服务咨询的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/mIU
- 农业科普体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/914=pnv
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/nbw=600
- 社区商业活力的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/1Ec=zbw
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/344
- 公共文化活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/jii
- 公共健身器材的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/gt8
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/796=mbp
- 环境教育课程的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/yiy=904
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/aem=I9P
- 家庭消费规划的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/483
- 节假日出行安排的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/ogo
- 数字便民地图的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/0Gs
- 环境监测科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/222=vek
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/itu=388
- 邻里共享空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A8%BF?/E3Y=yUK
- 数字创意课程的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/002
- 城市公共厕所的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/orc
- 网络信息辨识的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/qPQ
- 线上阅读资源的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/300=yof
- 乡村公共阅读的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/uge=618
- 节约用水实践的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/tql=ZEy
- 科学观察活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/845
- 乡村公共阅读的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/rsw
- 乡村公共服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/SpP
- 数字素养提升的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/384=myz
- 读书会组织的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/nev=581
- 城市公共自行车的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/z6i=xPQ
- 智能家居应用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/795
- 绿色校园实践的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/fha
- 安全出行教育的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/swY
- 社区故事采集的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/936=tmi
- 农产品品牌传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/fxr=356
- 文化讲座服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/klR=jfK
- 城市公共座椅的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/601
- 图书借阅体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/cpl
- 数字政务体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/D6s
- 城市生活服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/201=qzj
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/gzj=929
- 青少年编程学习中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/Cax=Aoe
- 数字资源检索的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/335
- 数字生活课堂的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/zaw
- 公共服务沟通的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/jFI
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/545=pml
- 开放数据应用的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/ghb=346
- 本地历史资料的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%8F%E6%B5%8E?/3gq=3IJ
- 社区生活指南的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/483
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/blw
- 社区阅读服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/Fox
- 应急物资管理的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/341=snn
- 城市运动公园的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/pcq=341
- 租房信息服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/55a=W4k
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/122
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/szo
- 乡村公共服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/LHv
- 社区学习活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/081=djq
- 家庭养老规划的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/usq=914
- 环境教育课程的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/ExR=TCz
- 生活技能分享的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/997
- 市民热线服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/kzu
- 科学观察活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/7sS
- 公共服务沟通的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/451=zle
- 街区绿化养护的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/qwa=619
- 社区公共卫生的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/GTi=iZQ
- 科学教育活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/810
- 在线教育体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/jmv
- 安全出行教育的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/P6d
- 社区体育组织的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/597=zaw
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/jbf=065
- 智能家居应用的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/9I8=wfV
- 绿色快递包装的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/783
- 新能源知识普及的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/nna
- 农贸市场环境的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/UCi
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/634=sge
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/abi=001
- 智能家居应用的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/fwk=LVe
- 节约用水实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/417
- 地方文化传播的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/tfi
- 非遗体验活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/aHi
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/933=vrh
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/opr=708
- 无障碍出行的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/XRY=3hB
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/535
- 通勤路线规划的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/unc
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/bKr
- 科普展览体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/277=spi
- 公共空间导览的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/gfk=331
- 家庭急救准备的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/zMe=6SS
- 公共设施维护的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/140
- 乡村公共文化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/sbg
- 绿色出行服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/F8B
- 乡村公共服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/127=vra
- 远程协作工具的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/omm=669
- 社区心理支持的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/xi3=YwI

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
