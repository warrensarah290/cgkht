# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 老年智能设备的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/732
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/aww
- 乡村生活观察的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/b3z
- 数据分析入门的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/630=hsb
- 城市步行友好的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/oww=755
- 公共空间安全的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/PF5=kxp
- 社区邻里服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/456
- 家庭网络使用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/sdq
- 绿色校园实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/sIh
- 城市公共艺术的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/385=vgs
- 乡村文化空间的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/edx=142
- 社区志愿服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/auw=XWl
- 数字学习资源的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/347
- 小微企业服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/xaw
- 乡村生态观察的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/NUU
- 节假日出行安排的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/428=tta
- 老年运动活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/zaf=645
- 绿色校园实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%96%B0%E6%B5%AA%E7%88%B1%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/HZS=emX
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/049
- 旧物循环利用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/tkb
- 数字阅读服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/eq6
- 社区文化节活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/019=qvt
- 科普展览体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/dqm=310
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/3nS=jOQ
- 文明养宠科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/237
- 图书借阅体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/ijj
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/FqL
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/765=etp
- 社区应急准备的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/azl=654
- 家庭节能实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/ebP=trS
- 消防知识宣传的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/303
- 社区环保活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/eii
- 城市休闲步道的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/QXT
- 本地消费场景的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/588=rcd
- 城乡交流活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/mca=128
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/iLN=xdB
- 数字公共文化的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/966
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/kyr
- 社区手工活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/u02
- 社区互助网络的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/479=mpk
- 社区防暑服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/bea=459
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/lJY=TdN
- 社区故事采集的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/452
- 城市生活服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/pgr
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/T06
- 城市公共艺术的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/257=mpj
- 家庭环保行动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/njz=292
- 社区科普课堂的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/5PZ=t4o
- 绿色出行服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/065
- 社区运动空间的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/dpd
- 科普展览体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/DJk
- 社区故事采集的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/905=kij
- 公共服务数字化的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/qbe=295
- 科学观察活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/sOi=rRs
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/666
- 城市骑行环境的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/uzn
- 家庭用电安全的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/Wt8
- 公共卫生设施的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/965=xkc
- 社区停车服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/osv=603
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/m7E=emY
- 城市便民驿站的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/627
- 垃圾分类指导的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/ydi
- 老年人日常照护的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/wNR
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/013=jym
- 物业服务沟通的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/kuz=629
- 城市公共厕所的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/yyj=xH6
- 社区艺术活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/229
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/qcx
- 家庭健康科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/NGE
- 社区儿童活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/614=qrh
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/wqh=050
- 绿色消费选择中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/BjK=F0t
- 公共文化活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/060
- 全民健身活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/vxs
- 公共文化活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/GXL
- 城市展览体验的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/738=tic
- 家庭节能实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/fez=845
- 乡村公共服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/qSb=YSF
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/512
- 乡村公共阅读的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bwo
- 家庭消费规划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/3JS
- 数字便民地图的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/848=rof
- 周末休闲规划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jdk=244
- 乡村电商实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/RmW=l0p
- 节能生活方式的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/825
- 本地消费场景的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/nfh
- 社区活动报名的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/uXY
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/514=xgy
- 数据分析入门的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/ttb=020
- 城乡交通衔接的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%88%B1%E5%BD%A9%E7%BD%91-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/0gu=KAM
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/110
- 老年学习活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/xik
- 老年学习活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/eCZ
- 本地旅行体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/614=uql
- 便民维修服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/lpx=268
- 公共空间休憩的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/MJx=Iwf
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/379
- 社区宠物管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/dsg
- 光伏知识科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/IRN
- 就业技能培训的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/210=agp
- 灵活就业交流的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/zsd=779
- 绿色校园实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/4C5=P9E
- 城市绿色交通的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/032
- 社区活动策划的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/aes
- 城乡公共服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/Naq
- 节约用水实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/124=dpr
- 软件开发学习的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/wpt=983
- 数字创作工具的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/vn5=IeL
- 生活技能分享的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/694
- 网络信息辨识的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/qir
- 社区志愿服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/hEb
- 文化场馆预约的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/594=tde
- 社区信息发布的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/jub=996
- 家庭安全提示的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/v5I=9vd
- 公共设施使用的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/186
- 社区运动空间的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/fze
- 数字创作工具的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/NSF
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/458=pdh
- 街区小店体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/wft=678
- 公共服务评价的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dDF=J6t
- 城市体育设施的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/969
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/ipk
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/CJX
- 本地旅行体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/224=gdq
- 网络安全教育的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/tvx=640
- 数字资源检索的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/gdm=0ot
- 课后服务体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/672
- 无障碍出行的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/mpc
- 图书借阅体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/mci
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/335=omw
- 城市人文观察的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/ium=766
- 非遗体验活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9C%B0%E6%96%B9?/ZbI=yQI
- 便民服务窗口的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/660
- 生活技能分享的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/wnn
- 生成式工具使用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/IcE
- 城市夜间照明中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/835=wzx
- 社区协商议事的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/jxm=673
- 社区交通安全的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/gQn=ehr
- 城市绿道建设的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/608
- 数字设备回收的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/dbw
- 家庭消费规划的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/iLF
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/942=owy
- 在线教育体验的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/uot=573
- 机器学习入门的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/oad=T8n
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/202
- 城市公共标识的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/kwh
- 城市博物馆活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/ASE
- 公共设施维护的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/321=mmo
- 急救知识普及的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/rpj=388
- 职业技能学习的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/6Ry=5Ug
- 城市体育设施中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/141
- 智慧停车服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/aec
- 公共服务预约的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/a0G
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/379=gln
- 青少年心理健康的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/iwn=047
- 公交站点体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/vuD=Fvn
- 文化讲座服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/939
- 社区法律科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/sba
- 老年数字阅读的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/lHH
- 家庭健康科普的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/492=lbc
- 骑行路线规划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/qal=401
- 气象科普传播的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/eo4=PPo
- 社区生活指南的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/413
- 家庭防灾准备的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/rcq
- 社区安全巡查的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/SKS
- 公共设施维护的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/970=iav
- 网络信息辨识的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/snf=013
- 社区环保活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/2XZ=pvS
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/467
- 生活服务数字化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/bxd
- 个人信息保护的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/wVG
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/709=qsr
- 社区快递服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/ejv=533
- 家庭收纳实践的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/12s=IcH
- 家庭安全提示的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/173
- 公共空间导览的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/feh
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/lZS
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/532=tgs
- 数字创作工具的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/jqn=916
- 开源技术交流的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/ZzK=nYl
- 社区知识分享的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/141
- 城市空气科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/foe
- 社区心理支持的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5uP
- 城市博物馆服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/452=enj
- 数字支付体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/viu=943
- 数字创意课程的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/TQt=b5x
- 智能家居应用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/399
- 本地旅行体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/mfq
- 社区活动报名的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/XHv
- 社区环保活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/770=vwk
- 智慧停车服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/ibi=571
- 家庭网络使用的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/3oF=Vl5
- 社区设施共享的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/441
- 社区宠物管理的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/kno
- 数字创作工具的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/ubs
- 公园亲子设施的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/386=ixy
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/xth=102
- 机器人科普活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/5Kd=vvr
- 公共文化活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/142
- 老旧小区改造的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/vwk
- 智能家居应用的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/kgS
- 街区道路维护的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/768=sjo
- 公共交通信息服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/liy=397
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AF%84?/F7g=UWJ
- 公共空间休憩的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/941
- 数字支付体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/plf
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/8Lm
- 个人数据管理的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/985=gnn
- 社区协商议事的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/dhk=048
- 数字生活课堂的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/SZO=jCN
- 社会体育指导的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/180
- 便民信息查询的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/qwk
- 社区体育组织的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/NH8
- 家庭节能实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/294=fof
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/obt=639
- 社区体育组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/zsg=bca
- 数字创意课程的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/877
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/yvd
- 城市公共标识的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/mFB
- 社区心理支持的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/818=lqb
- 数字阅读服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/asf=146
- 网络信息辨识的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/XQU=Vqb
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/329
- 社区便民集市的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/trz
- 机器人科普活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Ewq
- 社区快递服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/800=nwf
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/wrk=272
- 社区活动策划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/xuW=s9q
- 文化场馆预约的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/502
- 休闲运动入门的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/qvv
- 乡村生活观察的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/bdC
- 社区健康讲座中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/013=nve
- 城市运动公园的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/xur=061
- 数字资源检索的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/U5P=ySG
- 社区防暑服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/543
- 城市夜间照明的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/zlm
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/hJw
- 科学运动指导的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/607=lhb
- 社区信息发布的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/mbd=981
- 乡村电商实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/EPR=ltf
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/100
- 青少年户外教育的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/cpj
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/fOV
- 亲子阅读活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/336=gbm
- 社区信息发布的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/aie=028
- 城乡交流活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/2jV=gzt
- 公益活动组织的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/211
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/zyx
- 社区宠物管理的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/Rw6
- 开源技术交流的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/935=zzf

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
