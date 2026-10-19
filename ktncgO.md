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

- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/abl=540
- 校园安全教育的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%99%9A%E6%8A%A5?/sKx=tcY
- 数字创作工具的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/919
- 小区停车协商的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/hlc
- 公园亲子设施中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/Qhx
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/228=xdb
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/wrt=530
- 城市生活记录的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/Jpc=hFL
- 公共空间照明的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/604
- 城市文化路线的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/cpn
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/oKy
- 户外活动组织的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/140=phg
- 社区共享书架的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/wbt=357
- 社区艺术活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/t3y=x9n
- 公共服务评价的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/932
- 数字档案服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/att
- 垃圾分类指导的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/joT
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/127=vxx
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/ixd=968
- 创业经验分享的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/VgW=vrj
- 城市公共艺术中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/233
- 线上办事服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/ern
- 城市共享单车的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/JKd
- 城市建设科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/331=jig
- 城乡交流活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/lec=468
- 家庭防灾准备的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%B8%E5%95%86?/9vk=Yta
- 城市展览体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/299
- 青少年编程学习的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/srr
- 社区邻里服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/LQd
- 街区更新实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/961=uny
- 市民意见收集的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/ofl=268
- 社区活动空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-APP_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/tgs=j8I
- 社区安全巡查的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/135
- 气象科普传播的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/vdf
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/iNR
- 数字创意课程的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/701=owl
- 小区电梯维护的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/nvc=158
- 城市建设科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%99%9A%E6%8A%A5?/Uqf=xqI
- 社区教育资源的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/161
- 城市文明实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/oax
- 社区商业活力的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/t2P
- 市民意见收集的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/784=hyr
- 乡村生态观察的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/tir=462
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/SPZ=myr
- 社区便民集市的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/597
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/gso
- 城乡交流活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/IUK
- 绿色生活实践的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/995=sum
- 城市公共饮水的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/qbs=784
- 新能源出行的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/Kbi=JxE
- 应急物资管理的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/805
- 健康饮水科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/qhm
- 垃圾分类指导的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/YXb
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/085=zkw
- 数字设备回收的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/tbx=560
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/FzI=qUl
- 文化场馆预约中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/551
- 社区互助网络的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/byl
- 公共设施维护的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/RWr
- 食品安全科普的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/375=dxz
- 远程协作工具的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/xoc=550
- 骑行路线规划的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/jH5=n63
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/895
- 小区公共照明的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/uie
- 休闲运动入门的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/CD6
- 租房信息服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/373=qpm
- 社区安全巡查的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/mev=706
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/19y=ZlP
- 软件开发学习的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/909
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/ieq
- 医院导诊服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/7eu
- 公共交通接驳的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/355=ogi
- 骑行路线规划的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/rxp=354
- 通勤路线规划的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/s7P=lrB
- 城市绿道建设的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/429
- 社区法律科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/jpq
- 节约用水实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/Zgz
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/995=ifj
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/oqy=490
- 小区电梯维护的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/L7g=ZQp
- 小区停车协商的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/227
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/wwc
- 邻里共享空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/vIm
- 社区生活指南的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/088=iwj
- 儿童户外活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/kxu=483
- 公共场所导视的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/m5o=nkJ
- 社区协商议事的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/292
- 网络信息辨识的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/fki
- 绿色消费选择的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/Dis
- 家庭健康管理的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/311=pch
- 读书会组织的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/ion=368
- 图书馆活动策划的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/hvM=fkT
- 家庭用电安全的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/191
- 基层健康服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/jmq
- 老年人文化生活的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/bgi
- 公共交通信息服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/826=lcf
- 公共场所导视的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wlu=122
- 公共卫生设施的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/sSU=y2C
- 数字地图应用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/301
- 城市公共座椅的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/bjl
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/ggZ
- 远程协作工具的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/261=nre
- 数据分析入门的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/cxu=592
- 机器人科普活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A8%BF?/yym=gwB
- 无障碍出行的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/695
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/qmn
- 城市雨天出行的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/6Mr
- 科普展览体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/857=gzy
- 节能家电使用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/gph=193
- 社区手工活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/qrz=K37
- 青年志愿活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/007
- 全民健身活动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/xjz
- 社区艺术活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/J2V
- 家庭节能设备的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/458=lxz
- 公共空间照明的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/zif=415
- 社区活动报名的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/Z50=mU3
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/985
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/edo
- 街区更新实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/GyW
- 社区活动空间的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/244=vdl
- 图书馆活动策划的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/wze=373
- 基层健康档案的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/ySp=gYu
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/649
- 校园社团活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/cuy
- 社区老年食堂的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/aZs
- 网络安全教育的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/821=zie
- 社区垃圾分类的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/xdl=808
- 居家适老化改造的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/5u5=fmS
- 公共服务沟通的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/071
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/nfx
- 老旧小区改造的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/E4l
- 城市应急科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/947=aag
- 网络信息辨识的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/hij=021
- 智慧城市体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/Y72=vMe
- 公共场所导视的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/262
- 农产品品牌传播的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/elm
- 城乡交通衔接的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/rik
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/338=vge
- 城市体育设施的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/uzb=720
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/l2C=vdd
- 公共空间导览的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/005
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/tyn
- 老年友好服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/fKt
- 乡村文化活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/095=wtn
- 本地消费场景的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/opc=530
- 人工智能科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/Idm=FK8
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/854
- 社区手工活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/gmb
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/Sg1
- 数字素养提升的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/029=dpc
- 乡村生态观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/ako=149
- 老年人文化生活的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%BA%BA%E5%A4%A7?/LEF=B7v
- 课后服务体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/914
- 城市应急科普的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/rzg
- 个人数据管理的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/QHP
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/497=jcw
- 租房信息服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/svo=826
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_9898%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/QRX=zp8
- 城市空气科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/279
- 城市慢跑路线的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/dfc
- 绿色生活实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/ukm
- 环境教育课程的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/139=zpj
- 公共设施使用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/eoy=733
- 儿童安全出行的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%9B%B4%E6%92%AD?/k64=BOt
- 社区便民集市的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/277
- 校园社团活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/frk
- 开源技术交流的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/BL0
- 校园节能行动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/231=utr
- 社区设施共享的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/imx=534
- 数字地图应用的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/ylY=c2n
- 乡村教育资源的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/291
- 健康信息获取的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/jlb
- 数字素养提升的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/7p3
- 社区托育服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/574=qbp
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/cqz=750
- 社区法律科普的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/QpG=rwZ
- 数字素养提升的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/021
- 街道综合服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/zcc
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/PKs
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/856=mhy
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/lvu=251
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/oFz=6GV
- 社区公共卫生的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/253
- 校园阅读活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/mvx
- 家庭健康科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/qIo
- 健康饮食教育的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/091=hkr
- 社区商业活力的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/rxj=810
- 电动汽车充电的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/hC1=o1N
- 城市文化路线的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/260
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/nzd
- 城市夜间照明的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/kLH
- 节约用水实践的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/992=jyf
- 家庭收纳实践的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/svh=578
- 家庭健康管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/mcW=0ZJ
- 数字创作工具的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/567
- 公园亲子设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/pkw
- 儿童阅读角的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/dnc
- 城市微更新实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/429=shz
- 全民健身活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/lcc=058
- 绿色出行服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/jg9=Y68
- 志愿服务平台的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/633
- 绿色办公实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/ovi
- 城市公共厕所的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/KKR
- 青少年科技社团的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/073=vnw
- 食品安全科普的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/txv=259
- 城市可持续生活的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/BwF=tdK
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/922
- 城市空气科普的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/fgz
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/xar
- 数字公共文化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/255=gfm
- 公共服务数字化的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/zug=174
- 图书馆数字服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_9898%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/b1P=oMT
- 数字地图应用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/837
- 城市住房服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/vyw
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/bjy
- 小区公共照明中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/307=aml
- 骑行路线规划的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/jyi=015
- 乡村阅读活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/TrB=7CW
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/245
- 社区托育服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/jpj
- 课后服务体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/Moi
- 家庭健康科普的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/978=hup
- 绿色快递包装的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/ont=529
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_999%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BA%AA%E5%AE%9E?/Ems=hw9
- 生成式工具使用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/541
- 数字政务体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/lfz
- 城市展览体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/hPy
- 安全出行教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/341=uqv
- 乡村教育资源的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/zvk=160
- 社区家校合作的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/JQg=JPn
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/700
- 绿色校园实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/ydg
- 城市体育设施中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/uXg
- 地方文化传播的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/723=viz
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/kel=191
- 个人信息保护的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_999%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/4vm=Xuf
- 公共文化活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/517
- 学校食育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/yyy
- 家庭运动计划的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/wiT
- 基层健康档案的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/661=jep
- 户外活动组织的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/jpn=228
- 社区快递服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/t9m=9jC
- 社区交通安全的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/491
- 节约用水实践的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/fvs
- 通勤路线规划的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/aH9
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/543=oyv
- 城市文明出行的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/udi=842
- 家庭照护支持的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_999%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/ibl=twg
- 环境监测科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/260
- 儿童户外活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_999%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rdn

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
