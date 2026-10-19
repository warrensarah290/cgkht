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

- 公共卫生设施的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758cc%E5%AE%89%E5%8D%93%E7%89%8899_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/flu=009
- 公共空间安全的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758cc%E5%AE%89%E5%8D%93%E7%89%8899_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/Gva=6gB
- 无障碍信息设计的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/368
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/bdl
- 生成式工具使用的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/0oZ
- 乡村文化空间的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/454=qdo
- 基层服务创新的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/fzd=862
- 城市公共饮水的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/3uE=kvp
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/790
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/ijc
- 邻里互助活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/nrM
- 城市生活记录的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/115=bqn
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/nqd=085
- 科普展览体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E9%A3%8E%E9%99%A9_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/yTT=9Zf
- 环境教育课程的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/256
- 人工智能科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/uaq
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/miI
- 公共服务评价的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/220=fww
- 乡村文化活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/ihu=293
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/pKB=Eis
- 邻里共享空间的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/383
- 社区垃圾分类的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/cme
- 软件开发学习的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/gA1
- 老年学习活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/201=lgn
- 老年运动活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/gis=644
- 公共空间安全的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/Mcg=4db
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/505
- 社区快递服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/oxn
- 社区教育资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/kln
- 社区便利生活的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/402=tcv
- 绿色校园实践的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/txs=584
- 亲子科普活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E6%AD%A3%E8%A7%84_%E8%B1%86%E7%93%A3?/Jck=xML
- 绿色快递包装的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/930
- 城市慢行系统的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/gej
- 本地历史资料的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/RKI
- 城市步行环境的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/251=zpr
- 租房信息服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/zqj=725
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/NU3=9xF
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/873
- 科学教育活动的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/dfq
- 公共空间安全的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/vmj
- 街道综合服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/850=zwk
- 公共服务数字化的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/llz=928
- 小微企业服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/TuQ=AvU
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/788
- 城市文明实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ipj
- 无障碍出行的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/afw
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/352=wmv
- 城市步行友好的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/uhk=588
- 公共服务沟通的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90welcome%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/51b=jhh
- 文化讲座服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/811
- 线上阅读资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/rop
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/FtB
- 数字阅读服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/724=uvy
- 光伏知识科普的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/caf=205
- 科学健身方法的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%89%9B%E7%89%9B%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/GUK=zvN
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/980
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/nwl
- 健康饮食教育的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/cuU
- 小区公共照明的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/030=gmb
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/lhg=871
- 公园休闲体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/PoO=SYF
- 网络安全教育的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/604
- 数字支付体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/eva
- 数字设备回收的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/JAO
- 儿童友好空间的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/414=ulu
- 城市地名文化的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/uxd=361
- 儿童运动体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%A8%B1%E4%B9%90%E5%8A%A9%E6%89%8B_360%E6%97%85%E6%B8%B8?/Mvg=SwM
- 在线教育体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/469
- 日常摄影记录的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/jmo
- 家庭网络使用的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/S6X
- 老年友好服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/469=wjl
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/xrn=916
- 街头绿植养护的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/M9e=tuY
- 儿童友好空间的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/629
- 家庭饮食安排的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/avn
- 社区宠物管理中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/ZFW
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/909=vja
- 社区生活指南中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/ikz=897
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/PmA=YjE
- 绿色消费选择的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/865
- 科学教育活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/bxs
- 青少年编程学习的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/pY6
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/142=vld
- 社区设施共享的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/mqx=682
- 数字素养提升的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%AC%AC1%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/Ocf=6CN
- 本地历史资料的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/977
- 就业技能培训的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/wce
- 亲子阅读活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/R0g
- 社区便民服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/322=cic
- 社区科普课堂的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/gku=378
- 家庭环保行动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/3Yx=cvy
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/780
- 智能手机助老的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/noq
- 节假日出行安排的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/NAn
- 乡村公共文化的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/950=rgo
- 老年友好服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/cla=589
- 生活服务数字化的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/LqP=cg3
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/055
- 城市住房服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ayi
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/fqh
- 社区知识分享的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/165=etj
- 公共服务指南的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qzb=630
- 家庭节能设备的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/U2b=NGT
- 农业科普体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/657
- 本地消费场景中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/xqk
- 市民热线服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/XMp
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/021=psj
- 全民健身活动的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/kee=107
- 公共文化活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E7%BA%AA%E5%AE%9E?/c0D=K8c
- 公共空间安全的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/808
- 城市绿道建设的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/qgy
- 无障碍出行的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/yMb
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/481=yqp
- 小区公共照明的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/rwv=454
- 青年就业服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%AC%A7%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A8%B1%E4%B9%90_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/pMd=HEG
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/496
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/nkf
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/wAS
- 乡村教育资源的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/743=miv
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/tyy=065
- 社区儿童活动的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/Wx2=33h
- 文化场馆预约的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/027
- 城市公共厕所的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/evo
- 居家防滑改造的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/Npf
- 社区邻里服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/008=fkj
- 城市共享单车的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/ofy=817
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_66%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/kwO=fV0
- 数字政务体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/587
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/lxw
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/TRl
- 儿童友好空间的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/636=gbj
- 在线教育体验的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/sar=181
- 数字政务体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/RGM=t5h
- 农业科普体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/049
- 终身学习资源的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/onk
- 社区老年食堂的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/6CM
- 基层健康服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/590=bto
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/alp=163
- 社区科普课堂的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91welcome%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/Vbv=rr7
- 生成式工具使用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/014
- 周末休闲规划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/okk
- 社区快递服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/b6u
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/830=dpa
- 基层服务创新的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/trv=067
- 公共场所导视的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/HF0=Tyq
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/021
- 家庭运动计划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/ynt
- 城市体育设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/JPf
- 图书馆数字服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/668=wuj
- 非遗体验活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/jwq=397
- 绿色校园实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%81%E6%BE%B3%E9%97%A8%E5%B0%BC%E6%96%AF%E4%BA%BA%E6%89%8B%E6%9C%BA%E7%89%88%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/pKu=GCM
- 社区心理支持的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/273
- 家庭志愿活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/qcf
- 社区阅读服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/kzq
- 全民阅读推广的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/530=tcv
- 健康信息获取的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/jdb=268
- 公共空间导览的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/iak=Pzc
- 社区阅读服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/898
- 城市绿道建设的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/syz
- 邻里共享空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/hvT
- 城市步行环境的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/990=pec
- 公园休闲体验的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/tbt=894
- 乡村文化活动的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/spt=ODA
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/704
- 科普展览体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/xfu
- 消防知识宣传的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/hUr
- 城市文明出行的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/826=kwc
- 社区手工活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/qgl=635
- 日常摄影记录的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9B%B2%E8%89%BA?/zEL=a6y
- 骑行路线规划的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/221
- 老年智能设备的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/wyn
- 城市游园体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/cke
- 骑行路线规划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/884=cfn
- 城市应急广播的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/lgn=119
- 便民服务地图的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/kna=ceD
- 环境教育课程的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/349
- 社区故事采集的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/nba
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/XyH
- 数据分析入门的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/280=hie
- 线上办事服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/auk=433
- 公共服务咨询的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/ujd=okS
- 城市地名文化的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/967
- 乡村生活观察的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/zcl
- 周末休闲规划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/rd3
- 城市地名文化的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/218=dov
- 社区绿色空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/zhc=214
- 社区读书角建设的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/Nnr=JJl
- 基层健康档案的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/788
- 生活垃圾减量的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/iws
- 本地消费场景的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/QCD
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/654=hap
- 个人信息保护的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/ila=506
- 社区文化节活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/OSm=Khd
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/507
- 城市公共艺术中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/vcg
- 社区科普课堂的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/Vtu
- 安全出行教育中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/197=uzz
- 食品配送体验的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/lcf=431
- 数字资源检索的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/pOK=LOU
- 城乡公共服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/023
- 乡村公共服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/drb
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/pXM
- 公共文化活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/784=irz
- 公共场馆服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/rbj=159
- 社区运动空间的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%9B%98%E7%82%B9?/Dqt=Mi8
- 青少年编程学习的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/333
- 小区公共照明的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/rxa
- 数字资源检索的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/woF
- 线上阅读资源的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/600=yca
- 职业技能学习的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/xtm=610
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/OUK=vIR
- 健康信息获取的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/653
- 家庭健康管理的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/clq
- 图书馆数字服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/tk7
- 在线教育体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/671=oad
- 数字学习资源的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/izl=732
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/Cap=SME
- 食品配送体验的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/579
- 口袋公园建设的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/omy
- 便民服务地图的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/Tul
- 青年志愿活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/834=nqh
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/vkn=004
- 数字创作工具的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/Mfb=YUD
- 家庭运动计划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/108
- 城市夜间生活的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/urh
- 乡村电商实践的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/2dz
- 人工智能科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/878=kxj
- 城乡交通衔接的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/irh=529
- 乡村生态观察的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/bkT=UyQ
- 开源技术交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/012
- 数字学习资源的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/xtr
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/bom
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/942=oqm
- 公园无障碍服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/xad=354
- 公交站点体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/v68=i43
- 志愿者培训交流的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/798
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/wjm
- 智能家居应用的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/BO3
- 消防知识宣传的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/799=iit
- 机器学习入门的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/lcu=902
- 社区邻里服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/cA9=fUg
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/380
- 节约用水实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/jsl
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/OVf
- 老年人日常照护的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/286=xiz
- 家庭饮食安排的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/naj=305
- 社区设施共享的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%89%8B%E6%9C%BA%E7%89%88-%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/Yjo=BDJ
- 开源技术交流的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/246
- 城市微更新实践的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/xjh

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
