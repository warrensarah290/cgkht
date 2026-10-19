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

- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/ken=728
- 社区消防演练的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/1c1=oPF
- 农贸市场环境的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/227
- 旧物循环利用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/hql
- 网络安全教育的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/NXr
- 开放数据应用的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/500=ihe
- 药品使用科普的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/mnb=443
- 数字便民地图的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/7nC=UVh
- 日常摄影记录的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/687
- 绿色建筑理念的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/wdn
- 老年学习活动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/cKq
- 邻里互助活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/310=foc
- 生活垃圾回收的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/wdf=311
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/oWp=frn
- 学校体育活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/915
- 新能源知识普及的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/gaw
- 节能生活方式的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/7JR
- 社区志愿服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/430=ffi
- 软件开发学习的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/rim=631
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/qVh=5yF
- 休闲运动入门的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/529
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/iwb
- 社区法律科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/SZs
- 城市水环境观察的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/942=fhv
- 社区菜市场服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/jto=281
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/trq=6uy
- 公共空间导览的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/408
- 租房信息服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/vto
- 数字素养提升的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/hfi
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/415=rwn
- 家庭环保习惯的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/loy=226
- 生活垃圾减量的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/ydP=5SQ
- 数字学习资源的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/669
- 乡村文化空间的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/goj
- 社区儿童活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/uHB
- 绿色办公实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/753=reo
- 城市文化路线的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/req=813
- 城市公共艺术的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/BJu=uf0
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/139
- 城市夜间照明的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/lcn
- 公共场馆服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/uxb
- 便民服务窗口的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/975=gxt
- 公共设施维护的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/mbj=611
- 读书会组织的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/9KE=AIB
- 家庭健康管理的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/346
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/vsi
- 骑行路线规划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/CMN
- 社区科普课堂的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/662=fbp
- 绿色建筑理念的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/yjk=844
- 新能源知识普及的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/MJS=CIR
- 校园社团活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/963
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/fcm
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/nki
- 公共服务咨询的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/958=fnb
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/bnu=921
- 绿色生活实践的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/Rqj=9FI
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/462
- 学校食育活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/zzf
- 公共服务预约的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/lpl
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/177=rqa
- 城市公共自行车的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/egd=831
- 社区消防演练的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/W9t=m6u
- 农产品消费体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/150
- 家庭收纳实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/fhd
- 软件开发学习的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/Fwh
- 学校食育活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/419=dxf
- 科学教育活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/uyw=769
- 在线教育体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E9%9F%B3%E4%B9%90?/84U=DL1
- 城市夜间生活的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/781
- 城市基础设施的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/coz
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/Fai
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/239=pvw
- 乡村阅读活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/jkj=154
- 软件开发学习的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/6xN=H08
- 家庭安全提示的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/109
- 家庭急救准备的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/amd
- 公共设施使用的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/KVB
- 人工智能科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/239=rrl
- 家庭养老规划的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/kfc=404
- 图书馆活动策划的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/rRC=qEi
- 消防知识宣传的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/674
- 社区协商议事的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/nfi
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/CD1
- 街区小店体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/868=wdy
- 便民信息查询的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/ceu=271
- 休闲运动入门的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/UL4=FLc
- 城市地名文化的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/344
- 家庭网络使用的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/fzq
- 青少年科普实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/YvZ
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/548=kyx
- 社区信息发布的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/mnz=191
- 便民服务窗口的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/Ckd=JNe
- 街区绿化养护中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/700
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/hdy
- 儿童安全出行的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/ZDs
- 家庭节能实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/647=uid
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/onf=645
- 老年运动活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/0aw=QHV
- 社区交通安全的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/721
- 周末休闲规划的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/zwg
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/E1m
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/006=gqu
- 社区手工活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/vba=908
- 本地消费场景的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%A5%BC%E5%B8%82?/45S=eFW
- 网络安全教育的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/221
- 青少年科技社团的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/rfy
- 本地消费场景的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/IX0
- 安全出行教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/961=dro
- 社区防暑服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/fbj=789
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/qgH=VM1
- 公共卫生宣传的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/419
- 城市公共艺术的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/oxh
- 绿色校园实践的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/ZGN
- 社区公共议事的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/280=biv
- 城市休闲步道的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/ilp=412
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/W1n=1zs
- 在线学习体验的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/585
- 家庭消费规划的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/pgj
- 市民热线服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/dCq
- 老年数字阅读的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/942=fon
- 社区垃圾回收的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/ynx=851
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/oWy=pmW
- 公园休闲体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/302
- 公共空间照明的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/qbr
- 城市空气科普的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/wBg
- 儿童友好空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/325=cku
- 志愿者培训交流的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/zur=591
- 数字创意课程的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/1g7=KYt
- 城市住房服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/748
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/pmg
- 节能家电使用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/nnq
- 跨代沟通活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/651=nwm
- 家庭防灾准备的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/stv=022
- 公共交通接驳的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/zcs=dgQ
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/216
- 智慧城市体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/uyj
- 地方旅游导览的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/j7d
- 租房信息服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/564=biz
- 乡村生态观察的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/xul=185
- 城市休闲步道的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/Hd9=N9f
- 公交站点体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/237
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/rcm
- 家庭养老规划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/4Rr
- 农产品品牌传播的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/667=fjj
- 休闲运动入门的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/fca=251
- 城市博物馆服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%97%AE%E7%AD%94?/ybK=pTM
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/735
- 公共空间导览的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/twe
- 社区花园共建的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/q6K
- 文明养宠科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/434=nxu
- 社区活动报名的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/dkn=799
- 数字政务体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/7GM=C70
- 老年友好服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/426
- 社区法律科普的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/dcc
- 绿色快递包装的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/sGi
- 社区读书角建设的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/374=mil
- 城市便民驿站的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/dzd=825
- 城市慢跑路线的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/YKh=LwJ
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/967
- 节气饮食文化的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/csu
- 社区公共卫生的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/Tdo
- 社区公共议事的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/965=bzt
- 校园社团活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/pno=758
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%98%9F%E5%BA%A7?/h6P=YMC
- 绿色出行服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/592
- 社区科普课堂的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/spf
- 乡村生态旅游的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/K1l
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/205=qtg
- 城市文化路线的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/gpi=070
- 物业服务沟通的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/QzK=fUg
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/493
- 文化讲座服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/agm
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/G1O
- 城市人文观察的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/070=gzl
- 社区休闲设施的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/wrp=967
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/1bW=CGi
- 小区停车协商的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/554
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/gja
- 在线学习体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/Y6w
- 日常摄影记录的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/134=reb
- 城市微更新实践的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/ceo=759
- 环境监测科普的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/0yF=YAK
- 创业经验分享的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/630
- 城市公共自行车的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/hma
- 居家适老化改造的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/JOj
- 社区学习活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/629=vos
- 社区文化节活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/sgp=334
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/se0=HMk
- 社区邻里服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/553
- 食品配送体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/wqs
- 职业技能学习的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/p8p
- 地方文化传播的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/453=ilo
- 城市体育设施的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/pjh=283
- 智慧城市体验的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/4sy=5VE
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/251
- 城市雨天出行的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/qfg
- 儿童运动体验的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/foO
- 社区儿童活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/594=vix
- 绿色消费选择的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/pln=515
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/X8u=0Fi
- 青年志愿活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/197
- 公共服务咨询的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/tbj
- 社区商业活力的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/424
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/869=ilh
- 基层健康服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/ztj=684
- 儿童阅读角的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%92%AD%E6%8A%A5?/qLl=TOf
- 光伏知识科普的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/980
- 基层服务创新的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/axq
- 图书馆数字服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/rjA
- 居民健康教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/324=zyf
- 数字政务体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/umx=909
- 社区菜市场服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/0iS=Vsi
- 职业技能学习的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/131
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/tkn
- 公共卫生设施的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/QMx
- 社区文化节活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/715=tkl
- 电子商务服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/uwr=831
- 垃圾分类指导的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/5dX=KIi
- 数字设备回收的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/199
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/rsj
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/QUX
- 数字政务体验的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/990=lou
- 儿童运动体验的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/itz=340
- 数字公共文化的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/zmF=a0w
- 社区休闲设施的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/139
- 数字地图应用的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/iiv
- 机器人科普活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/cj0
- 社区信息发布的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/450=ijm
- 基层健康档案的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/wxd=881
- 老年智能设备的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/Z5N=ntO
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/332
- 智能手机助老的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/lbx
- 环境教育课程的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/NuE
- 城市公共空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/312=wyo
- 社区消防演练的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/jrd=874
- 个人信息保护的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/2Ur=4LM
- 亲子科普活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/358
- 节能生活方式的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/pem
- 儿童安全出行中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/I0e
- 社区宠物管理的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/958=okn
- 本地旅行体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/clf=146
- 应急物资管理的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ev8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/Krs=MlY
- 乡村公共文化中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/902
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/ush
- 城市文明实践的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/8Cq
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/971=hkh
- 城市公共厕所的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/zqh=677
- 乡村公共服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/GX2=ndk
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Ev8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/343
- 开源技术交流的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9Ev8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/jsm

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
