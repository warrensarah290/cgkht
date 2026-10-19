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

- 城市噪声观察的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/luo=487
- 社区停车服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/751=d5j
- 基层健康档案的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/263
- 公共文化活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/jcu
- 志愿服务平台的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/DEn
- 家庭消费规划的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/410=qmt
- 农产品消费体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/obd=557
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_360%E5%BD%A9%E7%A5%A8%E4%BC%98%E5%8A%BF%E8%A7%A3%E6%9E%90_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/q8R=kLO
- 社区互助网络的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/340
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/ked
- 城市公共饮水的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/GNo
- 街区绿化养护中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/314=zmh
- 城市建设科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/ouh=144
- 节约用水实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_360%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/2JO=OFW
- 骑行路线规划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/137
- 乡村生态观察的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/pdp
- 城市博物馆活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/H3y
- 基层服务创新的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/045=wjq
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/ege=627
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_360%E5%BD%A9%E7%A5%A8%E5%85%A8%E5%9B%BD%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/7Ui=dQm
- 青少年编程学习的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/010
- 城市生活服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/thh
- 城市社区治理的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/dXI
- 健康信息获取的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/955=zgw
- 传统手工艺体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/yfq=961
- 口袋公园建设的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_360%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/qET=0aF
- 家庭照护支持的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/921
- 城市游园体验的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/mpw
- 城市人文观察的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/Rhd
- 老旧小区改造的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/683=fig
- 城市骑行环境的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/kqt=578
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%BD%A9%E6%B1%87-welcome_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/aoa=JJX
- 骑行路线规划的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/036
- 家庭收纳实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/soj
- 食品安全科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/UW3
- 亲子阅读活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/572=lcp
- 社区知识分享的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/luh=047
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E8%B5%A2%E5%AE%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/iiy=LkL
- 公共设施使用的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/405
- 乡村文化空间的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/kpd
- 社区家政服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/viJ
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/722=uit
- 在线学习体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/wdf=300
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%BC%B9_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/Znl=SLA
- 城市展览体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/839
- 家庭志愿活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/cvp
- 家庭运动计划的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/0k1
- 青年就业服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/320=erw
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/smg=670
- 社区设施共享的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%BB%8A%E6%97%A5%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E4%B8%93%E5%AE%B6%E8%83%9C%E5%B9%B3%E8%B4%9F%E6%8E%A8%E8%8D%90_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/q5F=wkg
- 青少年编程学习的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/419
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/ofl
- 城市公共饮水的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/paL
- 乡村公共文化中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/205=orj
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/wgk=510
- 社区垃圾回收的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8cn_360%E6%97%B6%E6%8A%A5?/UUT=6EQ
- 城市噪声观察的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/289
- 口袋公园建设的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/qco
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/d8f
- 社区休闲设施的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/138=erw
- 公共交通接驳的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/ocd=789
- 社区故事采集的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8.com_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/1Ao=SmC
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/699
- 全民阅读推广的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/owq
- 光伏知识科普的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/K8W
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/943=yjc
- 儿童户外活动中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/qga=206
- 城市应急科普的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E4%BF%A1%E6%81%AF_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/umH=jew
- 城市步行友好的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/181
- 社区交通安全的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/pkp
- 家庭饮食安排的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/E0j
- 农业科普体验的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/557=uyo
- 家庭科学教育的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/kbt=138
- 乡村公共服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/KKZ=Dxq
- 市民热线服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/182
- 青少年编程学习的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/txr
- 社区快递服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/eD3
- 社区活动策划中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/820=uko
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/bkp=822
- 图书借阅体验的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/yVJ=kud
- 文明养宠科普的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/870
- 个人数据管理的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/ojg
- 城市文明实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/4H2
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/324=dps
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/rtz=987
- 公园亲子设施的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_58%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/9zb=7DN
- 数字资源检索的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/036
- 传统节日科普的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/dyn
- 城市地名文化中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/7UF
- 线上办事服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/189=vqp
- 农村环境治理的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/faa=445
- 低碳社区实践的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_58%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%83%AD%E6%A6%9C?/868=PLc
- 邻里互助活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/392
- 公共服务咨询的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/crr
- 数字便民地图的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/Hip
- 地方民俗记录的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/971=yaw
- 公共场馆服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/glz=530
- 健康信息获取的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_u588vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/zti=1YS
- 社区活动报名的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/878
- 乡村产业科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/vqp
- 绿色校园实践的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/eFD
- 科学健身方法的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/299=ikz
- 城市公共座椅中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/pni=974
- 校园阅读活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/Cla=ZH6
- 医院导诊服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/821
- 智慧停车服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/iex
- 就业技能培训的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/BZZ
- 家庭安全提示的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/645=spv
- 社区活动策划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/vfa=575
- 消防知识宣传的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8777_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/xoo=zLE
- 社区停车服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/388
- 科普展览体验的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/ukn
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/nmQ
- 户外活动组织的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/285=cjt
- 儿童友好空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/vom=294
- 社区故事采集的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_777%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/Y5l=CtB
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/669
- 城市建设科普的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/nys
- 社区知识分享的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/ZI8
- 在线学习体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/376=zjc
- 信息无障碍体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/tnz=487
- 老年人日常照护的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_777%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/lMU=O93
- 数字课堂应用的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/939
- 运动安全知识的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/ltw
- 农产品消费体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/nsv
- 城市休闲步道的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/535=tpc
- 儿童安全出行的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/lum=321
- 乡村生态观察的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/NGn=uyJ
- 居家防滑改造的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/340
- 城市慢行系统的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/phh
- 校园社团活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/r5G
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/240=xsk
- 城市公共艺术的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/teo=139
- 农业科普体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_777%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/Bsy=MaF
- 家庭用电安全的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/347
- 农产品品牌传播的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/rfm
- 健康饮食教育的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/VzC
- 城市空气科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/589=iom
- 公共服务指南的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/pxh=393
- 校园安全教育的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_777%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/JOD=9B8
- 城市骑行环境的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/917
- 城乡公共服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/qvu
- 城市农夫市集的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/Kzc
- 校园节能行动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/610=ume
- 创业经验分享的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/zvi=750
- 社区互助网络的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_777%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/3yp=k4X
- 城市公共标识的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/025
- 开放数据应用的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/vyf
- 社区公共餐饮的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/sjD
- 职业技能学习的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/563=hiv
- 社区学习活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/ayr=045
- 数字支付体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/FAC=6t5
- 家庭消费规划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/940
- 在线学习体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/ofi
- 开源技术交流的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/1zL
- 本地消费场景的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/198=ghl
- 健康步道使用的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/uor=289
- 社区活动空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_01%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/Ang=fxP
- 骑行路线规划的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/441
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/nsm
- 家庭节能实践的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/mS6
- 公共空间安全的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/446=sct
- 健康饮食教育的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/hgr=985
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_158%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/0IN=GDq
- 家庭教育交流中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/559
- 社区邻里服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/eph
- 老年学习活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/Ndo
- 非遗体验活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/853=bkt
- 无障碍出行的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/wkj=087
- 小区公共照明的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_357%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/n6s=p6a
- 绿色办公实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/718
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/jyk
- 家庭用电安全的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/FOq
- 社区活动策划的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/631=wzf
- 社区共享书架的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/gbh=626
- 志愿者培训交流的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88_36%E6%B0%AA%E5%8F%B7%E5%A4%96?/8uh=kwV
- 公园亲子设施的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/090
- 城市雨天出行的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/udb
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/XI3
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/279=xjm
- 社区协商议事的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/rzb=562
- 文化场馆预约的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6__6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/QYJ=1QE
- 家庭环保习惯的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/428
- 青年就业服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/ooo
- 生活垃圾减量的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/K6h
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/222=qie
- 环境教育课程的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/isd=264
- 在线学习体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_6701%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/Vow=P5W
- 急救知识普及的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/475
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/oug
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/RDZ
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/536=pep
- 老年人出行服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/qeq=802
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_6G%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/D6i=Dxp
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/879
- 家庭安全提示的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/pdg
- 儿童运动体验的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/k0T
- 数字便民地图的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/904=thc
- 街道综合服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/ccl=066
- 校园节能行动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_6G%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/zSl=Gos
- 社区便利生活的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/546
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/dpg
- 生活垃圾减量的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/a18
- 公交无障碍服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/802=kun
- 食品配送体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/bvd=852
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_733%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%9F%BA%E9%87%91?/6bQ=i5A
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/484
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wvb
- 城市步行环境的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/395
- 周末休闲规划的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/959=jqp
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/aaz=499
- 社区快递服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_785.CC%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/HgG=Es0
- 社区邻里服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/536
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/wte
- 社区学习活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/lw6
- 城市应急广播的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/901=cjm
- 社区活动报名的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/qww=215
- 公共设施使用的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%87%B0%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%96%B0%E6%B5%AA%E5%BF%AB%E6%8A%A5?/UwD=gDB
- 开放数据应用的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/856
- 家庭饮食安排的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/rqm
- 青少年户外教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/zrI
- 应急物资管理的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/345=ruv
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/vsx=863
- 数字支付体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8cp785cc_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/B3x=qBW
- 社区商业活力的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/247
- 绿色出行服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/mfe
- 地方美食文化的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/XgE
- 应急物资管理的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/722=stw
- 社区绿色空间的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/ggk=249
- 乡村生活观察的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/Gto=zaJ
- 节假日出行安排的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/066
- 公共空间安全的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/vlj
- 社区信息发布的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/KW3
- 城市应急广播的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/939=uvb
- 青年职业探索的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/htd=307
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/Rfe=QjI
- 节能家电使用的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/246
- 社区手工活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/dtx
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/ahk
- 社区艺术活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/826=gyd
- 本地消费场景的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/pof=807
- 全民阅读推广的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8785cc%E6%97%A7%E7%89%88_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/PbD=BxJ
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/479
- 地方旅游导览的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/sjq
- 城市社区治理的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/w36
- 口袋公园建设的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/654=gkb
- 社区家政服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/jwe=403
- 社区托育服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/86J=rWj
- 城市公共饮水的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_959%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/418
- 社区商业活力的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_959%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/rhm

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
