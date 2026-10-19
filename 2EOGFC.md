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

- 非遗体验活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/961
- 乡村生活观察的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/khz
- 社区信息发布的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ynd
- 城市绿道建设的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/177=kxg
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vsw=545
- 城市应急科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Q6W=Xit
- 数字课堂应用的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/209
- 科普展览体验的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/yxs
- 社区垃圾回收的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/vNK
- 数字支付体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/618=yxb
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/hmy=395
- 基层服务创新的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_360%E5%85%AC%E5%BC%80%E8%AF%BE?/MKz=RIy
- 乡村公共服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/614
- 家庭照护支持的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/ajg
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/f2N
- 便民信息查询的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/565=pyp
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/ztc=361
- 城市休闲步道中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_36%E6%B0%AA%E5%BF%AB%E6%8A%A5?/qWv=TL0
- 居家防滑改造的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/534
- 小区停车协商的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/cbt
- 城市树木认养的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/0wR
- 图书馆活动策划的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/321=zum
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/wjy=493
- 数字创意课程的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/DfE=wyU
- 基层健康档案的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/994
- 科普展览体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/hke
- 乡村电商实践的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/lbG
- 城市绿色交通的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/847=dol
- 气象科普传播的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/gbg=466
- 街区道路维护的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/rM0=q4G
- 数字生活课堂的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/783
- 新能源出行的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/rop
- 城市生活服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/Rid
- 城市空气科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/939=epb
- 生活技能分享的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/yhz=048
- 城市共享单车的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/Gty=BtL
- 公交站点体验的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/924
- 城市基础设施的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/ght
- 城市应急广播的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/60O
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/017=vbd
- 传统节日科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/ige=489
- 数字设备回收的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/PLA=Cfq
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/062
- 社区公共餐饮的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/fck
- 城市博物馆服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/MOv
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/560=nec
- 儿童运动体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/otb=046
- 城市体育设施的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/qet=Fkk
- 数字课堂应用的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/000
- 生活服务数字化的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/qwf
- 科学运动指导的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/4RR
- 社区手工活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/689=tvq
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/xqr=233
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/QmK=SEe
- 校园社团活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/650
- 社区故事采集的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/ayf
- 城市博物馆活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/j3U
- 开放式学习空间的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/518=eae
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/hai=884
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/GiP=vwW
- 乡村生活观察的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/953
- 青年就业服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/zmm
- 城市骑行环境的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/wvk
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/813=vlo
- 非遗体验活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/zsv=237
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/n3H=N5F
- 家庭照护支持的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/840
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/cfd
- 图书借阅体验的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/dle
- 社区知识分享的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/948=ddt
- 家庭网络使用中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/xkv=236
- 节日文化体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/ifQ=H8s
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/193
- 健康步道使用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/ihr
- 城市游园体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/zDY
- 个人时间管理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/884=qyj
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/swc=263
- 家庭健康科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/OrM=Ihq
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/520
- 网络信息辨识的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/iwb
- 数字素养提升中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/D1M
- 城市农夫市集的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/625=wvp
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/liv=160
- 城市可持续生活的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/oJu=50i
- 社区故事采集的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/183
- 城市步行友好的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/nov
- 街道综合服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/5mY
- 科学观察活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/781=zxa
- 生活垃圾回收的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/jvh=282
- 乡村产业科普的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/NuU=CTV
- 气象科普传播的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/207
- 健康饮水科普的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/yun
- 社区心理支持的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/8KP
- 社区共享书架的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/033=jau
- 就业技能培训的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/dvm=870
- 环境监测科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/Kx0=dua
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/459
- 就业技能培训的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/csd
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/A4i
- 药品使用科普的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/688=zwl
- 城市文明出行的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/geh=480
- 城市雨天出行的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A6%82%E6%84%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/Wvn=VTt
- 科学观察活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/362
- 绿色生活实践的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/nxr
- 社区学习活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/iJc
- 通勤路线规划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/794=imo
- 城市共享单车的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/yhr=352
- 社区体育组织的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/GbG=8Eu
- 城市博物馆活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/251
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/qoq
- 地方文化传播的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/zvi
- 青少年心理健康的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/824=fng
- 环境监测科普的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/lpt=097
- 青少年编程学习的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/1rT=N41
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/729
- 便民维修服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/agy
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/5DE
- 公共文化活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/035=bdf
- 社区应急准备的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/xev=330
- 新能源知识普及的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/fHT=p5g
- 环境教育课程中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/281
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/ckn
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/olR
- 家庭消费规划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/526=uxi
- 健康信息获取的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/bxe=716
- 便民信息查询的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E4%BF%A1%E8%AE%BF?/TCE=oKB
- 个人信息保护的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/579
- 小区电梯维护的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/asq
- 社区托育服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/v6c
- 公共空间安全的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/452=cyn
- 数字创作工具的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/hpz=766
- 气象科普传播的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/4Bx=nwn
- 绿色建筑理念的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/072
- 青少年科普实践的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/vsd
- 图书馆数字服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/mOh
- 社区教育资源的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/172=kxn
- 绿色生活实践的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/ttn=325
- 节假日出行安排的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/InX=ELj
- 城市噪声观察的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/921
- 校园节能行动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/ybx
- 读书会组织的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/YFT
- 日常摄影记录的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/434=ljk
- 数字素养提升的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/vpe=257
- 儿童阅读角的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85app_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/9h5=4wE
- 城市文明实践的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/991
- 公园亲子设施的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/jsq
- 社区志愿服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/O0q
- 家庭节能设备中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/670=ynz
- 文化讲座服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/evw=755
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%9C%80%E6%96%B0%E6%B4%BB%E5%8A%A8_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/Bxr=sSG
- 数字政务体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/749
- 公共服务沟通的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/fts
- 社区生活指南的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/WvP
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/915=sdi
- 儿童友好空间的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/wmo=518
- 软件开发学习的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E5%90%97_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/ji7=rOg
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/383
- 读书会组织的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/kdm
- 城乡交流活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/PHN
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/051=pxk
- 智能手机助老的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/rjz=848
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/KJz=SR4
- 家庭急救准备的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/876
- 公共服务数字化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/fpo
- 物业服务沟通的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/ysM
- 社区共享书架的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/698=tde
- 家庭节能设备的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/aij=351
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/R0P=3gp
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/849
- 健康信息获取的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/jmv
- 公共服务预约的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/iTP
- 公共交通信息服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/190=jfn
- 街区小店体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/dua=487
- 儿童友好空间的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%BF%99%E4%B8%AAapp%E5%AE%89%E5%85%A8%E5%90%97_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/GNs=WOH
- 城市公共空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/786
- 公园休闲体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/hqo
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/7Jp
- 个人数据管理的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/822=lzd
- 社区知识分享的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/frz=647
- 农村环境治理的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%B7%98%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/ARB=6zg
- 本地历史资料的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/850
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/myw
- 社区互助网络的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/X1O
- 地方戏曲体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/959=drz
- 青少年科技社团的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ldt=912
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/x8N=HaS
- 城市建设科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/024
- 绿色生活实践的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/cue
- 城市适老服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/Awn
- 垃圾分类指导的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/548=ukl
- 社区活动报名的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/grv=460
- 基层医疗预约的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%AE%98%E6%96%B9%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/g3H=NbC
- 公共服务数字化的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/701
- 公共场所导视的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/iet
- 社区商业活力的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/awD
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/379=hmd
- 社区生活指南的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/hen=190
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/e3g=s6b
- 节日文化体验的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/604
- 城市文化路线的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/mba
- 公共文化活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/lzP
- 节约用水实践的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/574=rbk
- 社区活动报名的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/tto=008
- 非遗体验活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E7%BB%8F%E6%B5%8E?/NLn=qsk
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/894
- 城市住房服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/tjq
- 数字学习资源的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/rdy
- 城市步行友好的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/381=lcz
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/iwz=557
- 便民信息查询的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/G38=BHg
- 青年志愿活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/614
- 城市运动公园的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/npe
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/r9l
- 老年人文化生活的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/567=ewf
- 老年人日常照护的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/wym=591
- 骑行路线规划的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/STH=bfI
- 绿色快递包装的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/064
- 新能源出行的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/lwb
- 科技馆参观体验的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/CO7
- 科学健身方法的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/010=opk
- 城市建设科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/kji=994
- 家庭养老规划的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/iCA=br3
- 乡村休闲旅游的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/682
- 社区学习活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/pkm
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/f6E
- 社区宠物管理的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/812=jmw
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/vab=048
- 社区活动空间的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/Hsl=hbN
- 环境教育课程的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/137
- 公共空间导览的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/pxe
- 开源技术交流的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/zMY
- 图书馆活动策划的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/029=hos
- 家庭理财科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/sqf=976
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/nX2=kBo
- 科普展览体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/455
- 城市生活服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/ueq
- 社区协商议事的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/bv8
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/639=xhu
- 社区教育资源的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/xwp=999
- 数字创意课程的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/ZQ1=HBc
- 药品使用科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/365
- 城市博物馆服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/zfo
- 市民意见收集的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/inj
- 数字公共文化的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/293=mwj
- 本地消费场景的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/aqo=980
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/Zte=tu8
- 数据分析入门的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/607
- 城市地名文化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/oyl
- 城市公共空间的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/vCX
- 城市运动公园的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/296=pnk

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
