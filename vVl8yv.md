# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 公共卫生宣传的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/953
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/gbg
- 数字阅读服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/76c
- 城市展览体验的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/885=fcv
- 家庭理财科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/eet=907
- 城市可持续生活的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/OXy=jlW
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/360
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/zoe
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/puq
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/364=gki
- 公共文化活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/udk=063
- 本地旅行体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/OsL=HCS
- 城市树木认养的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/640
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/rkx
- 便民服务地图的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/XSO
- 社区宠物管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/632=hvv
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/trg=582
- 社区快递服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/W80=dnY
- 文化场馆预约的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/674
- 公共设施使用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/pgw
- 户外活动组织的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/z6b
- 居家适老化改造的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/895=bjo
- 乡村电商实践中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/gqf=222
- 数字创作工具的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/uC5=YC0
- 地方民俗记录中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/720
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/htm
- 城市公共厕所的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/UQG
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/519=vml
- 城乡交流活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/ens=518
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/j44=Jrv
- 农村环境治理的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/606
- 在线教育体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/dfv
- 电动汽车充电的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/bMt
- 社区家校合作的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/635=ptx
- 居家适老化改造的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/zjb=835
- 校园节能行动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_75%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/lYJ=osO
- 公共交通接驳的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/923
- 社区老年食堂的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/ata
- 绿色消费选择的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/n6q
- 全民阅读推广的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/277=eyi
- 便民服务地图的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/ydx=551
- 绿色出行服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/J3t=eq6
- 社区便民集市的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/844
- 乡村文化活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/nos
- 数字便民地图的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/bi4
- 户外活动组织中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/966=dvm
- 青年志愿活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/lvo=708
- 科普展览体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/GGH=KRb
- 地方文化传播的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/014
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/fwf
- 社区公共卫生中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/5cX
- 数字设备回收的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/027=umr
- 农村环境治理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/lib=243
- 社区读书角建设的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/2tF=eH8
- 健康步道使用中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/815
- 个人信息保护的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/nbj
- 城市骑行环境的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/t4e
- 文明养宠科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/583=hep
- 绿色办公实践的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/zgt=986
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/i3j=egS
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/687
- 家庭消费规划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/tcb
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/FQP
- 社区家政服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/791=cty
- 家庭节能设备的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/lju=810
- 亲子科普活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/xdQ=tHq
- 公共设施维护的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/175
- 在线学习体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/qim
- 社区设施共享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/mBF
- 社区便利生活的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/829=xlc
- 校园社团活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/epr=097
- 校园安全教育的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/ebS=qdR
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/057
- 城市公共饮水的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/bfk
- 城市应急科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/3g7
- 乡村文化空间的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/825=ubn
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/ybn=502
- 城乡交流活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_75%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/abp=3l5
- 城市可持续生活的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/028
- 社区健康讲座的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/nrm
- 社区故事采集的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/SQV
- 街区道路维护的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/686=gtp
- 乡村公共服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/xcr=169
- 城市地名文化的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/DRl=wD8
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/501
- 老年人日常照护的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/hgl
- 乡村生态观察的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/azy
- 低碳社区实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/221=owr
- 软件开发学习的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/awh=693
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/Cmg=5BI
- 社区文化传播的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/174
- 城市雨天出行的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/pzq
- 终身学习资源的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/QaR
- 街区小店体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/950=khj
- 终身学习资源的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/ozc=700
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_7728%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/062=zRL
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/863
- 家庭运动计划的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/gek
- 市民热线服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/wAE
- 读书会组织的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/258=vrs
- 周末休闲规划的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/zsv=386
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/yzl=Qak
- 安全出行教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/409
- 青少年户外教育的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/wrd
- 数字便民地图的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/GkW
- 网络安全教育的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/749=lrx
- 公共服务指南的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/vlf=276
- 在线教育体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/Dr6=RW1
- 非遗课堂体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/871
- 全民健身活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/kaw
- 家庭阅读计划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/uBX
- 科学信息获取的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/966=dai
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/aof=416
- 生成式工具使用的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/nTs=YNE
- 数字学习资源的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/052
- 城市骑行环境的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/box
- 全民健身活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/u60
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/377=rws
- 社区文化传播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/hab=099
- 公共空间休憩的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/FDG=pwW
- 乡村公共文化的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/138
- 旧物循环利用的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/clq
- 数字创意课程的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/DYf
- 休闲运动入门的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/165=mvo
- 城市运动公园的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/cmj=195
- 家庭教育交流中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%82%E5%AF%9F?/LxF=57x
- 数字艺术创作的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/881
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/kgk
- 终身学习资源的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/mFW
- 公共服务评价中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/051=oik
- 智能家居应用的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/wwk=864
- 城市雨天出行的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/0YB=e1E
- 灵活就业交流的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/886
- 公共场所导视的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/sps
- 城市应急广播的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/hn5
- 社区安全巡查的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/646=tzw
- 公共交通接驳的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/ciy=295
- 数字支付体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/Ubs=8dE
- 青少年户外教育的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/296
- 城市生活服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/lnz
- 城市公共标识的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/xPZ
- 城市公共自行车的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/710=imx
- 农业科普体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/hqs=947
- 老年智能设备的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93?/EQu=An2
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/290
- 社区交通安全的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/qyv
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/g7v
- 骑行路线规划的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/230=cfg
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/jth=421
- 数字支付体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_7728%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/n14=XW0
- 线上办事服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/146
- 城市文明出行的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/fis
- 数据分析入门的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/xM9
- 乡村文化空间的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/599=sil
- 街头绿植养护的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/fkf=202
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/sLY=2dR
- 地方美食文化的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/090
- 城市应急科普的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/jek
- 生活垃圾减量的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/fJO
- 公共服务沟通的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/666=mzx
- 数字创意课程的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/upx=122
- 乡村公共阅读的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7728%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/lIo=uuT
- 数字艺术创作的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/369
- 健康信息获取的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/qqs
- 社区手工活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/zwR
- 乡村产业科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/317=gvq
- 智慧城市体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/abj=139
- 节气饮食文化的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_7728%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/FAb=L8i
- 社区花园共建的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/692
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/sec
- 绿色生活实践的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/ufH
- 家庭环保行动的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/207=wyf
- 城市共享单车的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/klw=635
- 社区科普课堂的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/AbM=LvF
- 城市生活服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/355
- 城市骑行环境的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/hjm
- 图书馆活动策划的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/hgH
- 社区活动报名中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/736=nad
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/oat=488
- 老年人出行服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/mxo=YZE
- 终身学习资源的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/586
- 社区共享书架的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/snt
- 社区家校合作的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/G8t
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/190=dal
- 家庭园艺实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/kad=487
- 儿童友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7728%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/1or=ZEC
- 个人数据管理的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/960
- 绿色消费选择的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/sfh
- 城市应急科普的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/Obv
- 社区学习活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/387=aeu
- 生活服务数字化的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/jgc=238
- 家庭用电安全的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_7728%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/JE4=B4R
- 公共服务咨询的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/870
- 开源技术交流的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/whs
- 城市公共饮水的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/uz7
- 绿色快递包装的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/672=yeu
- 气象科普传播的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ndt=503
- 节气饮食文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7728%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/S26=GIf
- 图书馆数字服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/142
- 社区儿童活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/qaa
- 社区便利生活的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/aK6
- 城市应急广播的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/247=nyb
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/cks=722
- 开放数据应用的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_7728%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/WtF=jqE
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/719
- 在线教育体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/zlr
- 城市应急广播的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/lQC
- 社区体育组织的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/381=zft
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/szf=297
- 便民维修服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_7728%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/hOk=EdG
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/504
- 文化讲座服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/plo
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/xIF
- 城市生活服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/253=qbo
- 远程协作工具的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/qcv=527
- 无障碍出行中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_7728%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ZCP=nRW
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/845
- 科学教育活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/ufc
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/pLw
- 青少年科普实践的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/694=ghb
- 社区故事采集的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/nxo=118
- 数字政务体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_7728%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/QBc=DFD
- 个人时间管理的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/636
- 儿童安全出行的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ekx
- 地方旅游导览的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/Hc9
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/681=glq
- 数字档案服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/bcs=358
- 老年学习活动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/DVl=mQl
- 街区道路维护的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/877
- 远程协作工具的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/hmu
- 社区宠物管理的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/QBS
- 机器学习入门的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/902=fxb
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/liw=607
- 城市步行友好的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_7731%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E4%BD%93%E8%82%B2?/Lr0=znj
- 家庭消费规划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/058
- 节约用水实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/mkz
- 社区环保活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/CPl
- 社区交通安全的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/816=svh
- 公共空间安全的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/hfk=626
- 城市展览体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/G3z=B4B
- 家庭食品保存的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/987
- 社区阅读服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/rlt
- 个人数据管理的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/2zk
- 节约用水实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/281=cvq
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/vnt=314
- 科学信息获取的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7731%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%A6%9C%E5%8D%95?/gL1=mSZ
- 小区公共照明的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_7731%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/584
- 校园社团活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_7731%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/lkw
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_7731%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/YhO
- 家庭节能实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_7731%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/360=lzd

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
