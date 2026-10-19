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

- 邻里共享空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/WfR
- 物业服务沟通的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/210=ciq
- 街区更新实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/eht=083
- 家庭健康管理的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/eca=vw3
- 绿色消费选择的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/763
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/vfd
- 青少年户外教育的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/hb4
- 新能源出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/047=tlw
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/ufe=012
- 社区修缮行动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/iCx=9Lp
- 城市夜间生活的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/973
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/deg
- 家庭节能设备的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/cZK
- 城市水环境观察的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/253=zfd
- 软件开发学习的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/jyf=763
- 科技馆参观体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/Sn2=l40
- 城市展览体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/071
- 学校食育活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/kzv
- 电子商务服务的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/VW0
- 农村环境治理的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/159=kxk
- 绿色校园实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/acf=787
- 便民服务窗口的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A7%91%E6%8A%80?/snG=dDi
- 社区手工活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/755
- 城乡交流活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/tee
- 家庭用电安全的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/ltF
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/313=wmy
- 智能手机助老的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/alm=510
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%AB%E7%9B%88iv-APP_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/vts=RZj
- 居民健康教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/242
- 城市住房服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/hzg
- 志愿者培训交流的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/HAh
- 社区生活指南的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/754=jpt
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/jhu=244
- 城乡交通衔接的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88iv-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/lXo=JoT
- 儿童安全出行的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/085
- 数字政务体验的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/yew
- 街头绿植养护的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/vHS
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/445=ydc
- 公共空间照明的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/mwq=528
- 家庭教育交流的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/3vw=MyL
- 城市微更新实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/066
- 小区停车协商的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/fan
- 社区运动空间的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/y28
- 社区活动策划的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/906=tei
- 职业技能学习中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/rkc=504
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88iv-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/4RN=L88
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/336
- 农产品品牌传播的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/ygh
- 全民健身活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/hQw
- 城市文明实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/038=num
- 城市可持续生活的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/uvy=286
- 公共设施使用的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88iv-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/Gyl=dOm
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/057
- 数字档案服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/vdn
- 地方文化传播的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/4XE
- 城市休闲步道的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/125=zii
- 社区邻里服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/kvs=099
- 个人时间管理的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88iv-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/qrN=mT1
- 家庭节能实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/011
- 节气饮食文化的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/iuj
- 家庭收纳实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/vVe
- 就业技能培训中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/831=jwz
- 城市公共艺术的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/yjt=059
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88iv-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/uVd=KIk
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/158
- 数字便民地图的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/hat
- 线上办事服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/9R3
- 家庭节能实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/424=hek
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/cfn=353
- 安全出行教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88iv-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/bqd=LtM
- 公共交通接驳的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/964
- 劳动教育实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/efs
- 科学教育活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/A1c
- 消防知识宣传的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/549=iyo
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/rot=101
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88iv-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/lKD=p5L
- 个人时间管理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/270
- 新能源知识普及的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/oxp
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/MCJ
- 数字公共文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/752=mcq
- 街区更新实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/qsl=509
- 家庭网络使用的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88iv-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/tBZ=2Qb
- 食品配送体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/338
- 老年友好服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/sry
- 城市农夫市集的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/g41
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/801=mrz
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/cbf=937
- 数字课堂应用的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88iv-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/4S3=yvv
- 居民健康教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/637
- 社区宠物管理的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/eyp
- 城市文明实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/Wv6
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/151=hak
- 社区公共卫生的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/twg=758
- 城市夜间照明的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/xYF=E4w
- 公园亲子设施的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/456
- 公共设施使用的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/sog
- 周末休闲规划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/fiH
- 城市社区治理的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/824=iyr
- 校园节能行动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/jxs=440
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/rCi=u47
- 非遗体验活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/083
- 绿色快递包装的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/glv
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/cqH
- 社区信息发布的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/606=aqc
- 开放数据应用的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/idd=178
- 线上办事服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/Urx=f8P
- 读书会组织的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/548
- 农村环境治理的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/duz
- 数字地图应用的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/UYF
- 乡村文化空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/558=tsg
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/lhq=134
- 公共卫生宣传的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/0bq=HIu
- 社区公共议事的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/252
- 城市骑行环境的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/juu
- 社区生活指南的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/Aoa
- 公共服务指南的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/123=muq
- 公共场馆服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/nbl=587
- 本地旅行体验的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/q64=R7U
- 农村环境治理的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/280
- 本地消费场景的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/szd
- 公共空间导览的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/jT2
- 节气饮食文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/758=ahr
- 社区消防演练的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/htf=816
- 休闲运动入门的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95welcome_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/gFB=Xz9
- 数字创意课程中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/003
- 城市公共标识的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/eev
- 传统手工艺体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/EQh
- 社区信息发布的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/936=slq
- 全民健身活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/wnj=663
- 地方旅游导览的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/ucM=hLb
- 无障碍信息设计的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/317
- 创业经验分享的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/jaz
- 社区商业活力的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/kYz
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/341=miu
- 便民信息查询的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/nlp=081
- 城市人文观察的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/BbA=nXo
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/327
- 青年职业探索的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/mpa
- 通勤路线规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/rld
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/034=jto
- 文化讲座服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/rzz=359
- 数字政务体验的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/TlN=gar
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/740
- 城市农夫市集的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/vip
- 便民维修服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/VOn
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/094=twb
- 绿色消费选择的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/ckc=136
- 机器人科普活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/QL9=GDE
- 智慧停车服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/190
- 图书借阅体验的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/ieh
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/Q1R
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/437=mce
- 志愿者培训交流的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/wvo=093
- 消防知识宣传的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88ll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/fIg=rfX
- 数字阅读服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/653
- 老年人出行服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/tia
- 数字便民地图的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/iLA
- 城市公共艺术的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/514=zfz
- 乡村教育资源的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/ovg=812
- 数字学习资源的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB%E7%9B%88ll-APP_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/a33=5YH
- 校园安全教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/696
- 节约用水实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/dmi
- 城市雨天出行的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/aDx
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/474=cfp
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/yke=557
- 健康步道使用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/78a=g3P
- 学校体育活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/885
- 健康饮水科普的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/gxa
- 社区菜市场服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/gI0
- 乡村公共服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/765=byl
- 街区小店体验的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/sec=066
- 职业技能学习的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/gLH=Z7n
- 居家适老化改造的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/048
- 网络信息辨识的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/bpm
- 社区托育服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/A38
- 公交站点体验的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/413=weq
- 线上阅读资源的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/bdq=325
- 城市噪声观察的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E7%9B%88ll-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/vc5=3N0
- 消防知识宣传的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/799
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/yxc
- 农村环境治理的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/Zff
- 地方文化传播的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/301=pyo
- 旧物循环利用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/dyz=671
- 乡村生态观察的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88ll-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/c0Z=KwG
- 社区便民集市的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/480
- 旧物循环利用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/ecq
- 小区公共照明的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/IOb
- 街区小店体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/103=iyf
- 食品安全科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/nqo=903
- 家庭养老规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88ll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/2Vj=c6U
- 消防知识宣传的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/709
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nlo
- 校园安全教育的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Zt9
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/974=ewk
- 网络信息辨识的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/adw=399
- 邻里互助活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88ll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/1RP=5iB
- 数字创意课程的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/498
- 社区运动空间的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/est
- 生成式工具使用的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/et8
- 家庭网络使用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/397=hsd
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/dwf=959
- 社区活动策划的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88ll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E5%B1%85?/nqT=g69
- 节能生活方式的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/502
- 城市雨天出行的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/bpo
- 儿童户外活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/oX1
- 传统节日科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/975=fga
- 学校体育活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/cqv=440
- 科学健身方法的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%A4%BE%E5%8C%BA?/ivj=VPr
- 乡村教育资源的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/334
- 市民热线服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/caw
- 读书会组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/4wb
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/247=raq
- 基层健康服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/tdj=977
- 绿色办公实践的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88ll-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/CVo=y5v
- 数字政务体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/203
- 社区生活指南的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/zgo
- 周末休闲规划的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/O1e
- 传统手工艺体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/989=fhd
- 小区电梯维护的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/hua=157
- 人工智能科普的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/2hM=7CV
- 城市便民驿站的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/858
- 儿童安全出行中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/jah
- 儿童阅读角的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/xSn
- 城市应急广播的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/062=zxj
- 青年就业服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/qgf=947
- 青年就业服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%9C%8D%E9%A5%B0?/lid=Gk7
- 便民维修服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/152
- 城市休闲步道的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/eag
- 公益活动组织的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/T5E
- 城市运动公园的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/933=pkh
- 旧物循环利用的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oid=306
- 城市绿色交通的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/AHH=IjW
- 电动汽车充电的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/621
- 社区花园共建的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/yqm
- 环境监测科普的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/7UB
- 文化场馆预约的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/029=dra
- 城市文明出行的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/rxy=465
- 生活垃圾减量的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/oNP=VBv
- 乡村文化空间的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/104
- 科技馆参观体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/ptg
- 公交无障碍服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/cMD
- 城市噪声观察的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/033=mnv
- 绿色校园实践的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/zny=922
- 科学运动指导的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/cue=NVJ
- 线上阅读资源的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/659
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/ged
- 家庭志愿活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/ygc
- 社区快递服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/746=ehq
- 机器学习入门的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/lce=591
- 数字课堂应用的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/oXo=Kt4

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
