# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 节能生活方式的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/spx=840
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/7I9=xBz
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/716
- 医院导诊服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/iyj
- 读书会组织的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/bU8
- 数字资源检索中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/682=rkg
- 租房信息服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/uza=744
- 校园社团活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/l78=K5H
- 城市噪声观察的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/865
- 基层健康档案的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/wbf
- 公交站点体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/xMa
- 节气饮食文化的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/550=mot
- 城市地名文化的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/dbh=586
- 街区道路维护中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/Gfl=x1l
- 乡村生态旅游的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/612
- 城乡交通衔接的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/vrm
- 健康饮食教育的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/X38
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/271=mqa
- 网络安全教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/lty=873
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/QuU=G7o
- 地方旅游导览的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/532
- 科技馆参观体验的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/dhu
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/JyL
- 城市公共空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/943=xid
- 社区公共议事的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/bqz=571
- 生活服务数字化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/dBR=SvD
- 人工智能科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/384
- 非遗体验活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/qhf
- 农业科普体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/g16
- 社区手工活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/887=riq
- 科学教育活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/zij=088
- 家庭运动计划的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/O6b=W9e
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/996
- 社区安全巡查的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/vgv
- 社区公共卫生的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/TBG
- 环境教育课程的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/103=ano
- 城市应急科普的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/doi=728
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/dMi=yhW
- 社区信息发布的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/287
- 乡村生活观察的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/apw
- 城乡交通衔接的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/Yio
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/841=oty
- 志愿者培训交流的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/qzs=380
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/SsG=SKk
- 青少年科技社团的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/447
- 公共健身器材的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/dej
- 气象科普传播的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/5pz
- 街道综合服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/082=ych
- 周末休闲规划的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/xuf=027
- 城市公共饮水的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/TNq=Xr6
- 图书借阅体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/488
- 医院导诊服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/amw
- 家庭环保行动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/xF6
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/245=ixy
- 公共场所导视的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/mbb=170
- 公园休闲体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/E8p=i39
- 科技馆参观体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/252
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/zwr
- 乡村教育资源的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/cUc
- 城市应急科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/181=esq
- 城市绿色交通的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/jux=257
- 城市农夫市集的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/pnV=heD
- 小微企业服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/819
- 乡村电商实践的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/wyj
- 消防知识宣传的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/BFw
- 城市文明出行的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/547=bpn
- 家庭饮食安排的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/hji=585
- 校园节能行动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/dnr=KP4
- 社区绿色空间的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/311
- 小区电梯维护的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/mbj
- 智能手机助老的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/Ql3
- 儿童阅读角的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/007=jag
- 生成式工具使用的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/rkd=957
- 远程协作工具的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/OlR=tne
- 城市住房服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/406
- 乡村产业科普的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/jvm
- 乡村电商实践的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/2K5
- 乡村产业科普的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/616=ger
- 公交站点体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/gle=433
- 数字创作工具的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%8D%9A%E5%AE%A2?/Qho=Gt7
- 家庭用电安全的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/807
- 社区科普课堂的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/vcl
- 基层健康档案的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/1g1
- 街区道路维护的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/720=scr
- 家庭急救准备的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/yxp=289
- 城市步行友好的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/qPX=T5a
- 骑行路线规划的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/943
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/cug
- 消防知识宣传的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/C4B
- 乡村电商实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/188=hsk
- 居家防滑改造的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/efv=875
- 公交站点体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vzK=F7h
- 街道综合服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/339
- 读书会组织的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/mkv
- 儿童运动体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/feE
- 社区邻里服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/053=eft
- 社区交通安全的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/hqw=563
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/Xtu=f23
- 公共图书馆服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/089
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/hze
- 绿色办公实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/miP
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/171=wug
- 节约用水实践的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/tae=805
- 公共设施使用的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/DhB=uzl
- 读书会组织的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/704
- 城市步行环境的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/tpg
- 智慧城市体验的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/wA7
- 家庭收纳实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/888=qme
- 本地消费场景的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/otf=041
- 安全出行教育的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/GrR=HdZ
- 智能手机助老的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/753
- 社区快递服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/bzj
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/UpJ
- 安全出行教育的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/331=ecj
- 在线学习体验的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/nyu=378
- 公共服务预约的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/2wA=UI5
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/292
- 生活垃圾减量的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/bxw
- 骑行路线规划的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/LNs
- 数字阅读服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/267=bff
- 本地历史资料的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/cmq=272
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/kkM=9Jx
- 老年学习活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/515
- 社区信息发布的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/mcr
- 乡村文化空间的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/zN5
- 家庭教育交流的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/818=kqr
- 社区信息发布的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/pne=558
- 机器人科普活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/Ivx=TSQ
- 便民维修服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/436
- 图书馆数字服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/hgy
- 绿色生活实践的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/ojK
- 个人信息保护的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/695=evl
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/trh=673
- 传统手工艺体验的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/HwA=nJn
- 校园安全教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/060
- 公益活动组织的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/yxp
- 公共服务咨询的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/Qq0
- 节日文化体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/587=saq
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/aem=461
- 乡村文化空间的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/5bm=0Yk
- 志愿者培训交流的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/209
- 城乡交流活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/ltj
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/TZ7
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/155=ufa
- 社区法律科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/lrq=886
- 城市共享单车的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/9Fc=SVM
- 家庭消费规划的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/091
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/ccf
- 儿童户外活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/ZiP
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/415=pla
- 街区绿化养护中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/yhp=029
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/Cc6=13A
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/510
- 图书借阅体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/ice
- 读书会组织的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/ZLz
- 农村环境治理的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/921=ybt
- 社区教育资源的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/yri=474
- 便民维修服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/Hqf=sux
- 环境教育课程的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/160
- 社区家政服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/ohw
- 城市绿色交通的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/bkO
- 公共服务数字化的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/506=wmd
- 地方戏曲体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/muy=778
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/y6A=Dgz
- 本地消费场景的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/565
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/ule
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/6sg
- 公共空间休憩的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/150=ipn
- 城乡交流活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/msu=513
- 电动汽车充电的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/Xux=wuc
- 城市步行环境的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/911
- 城市可持续生活的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/eqk
- 城市公共座椅的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gN4
- 食品安全科普的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/280=gya
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hnl=602
- 开源技术交流的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7BD=AUJ
- 家庭收纳实践的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/409
- 城市夜间照明的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/ikp
- 街区绿化养护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/MGM
- 基层服务创新的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/960=grk
- 社区科普课堂的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/apt=305
- 无障碍出行的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/XFU=NlA
- 学校体育活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/795
- 网络信息辨识的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/lvx
- 课后服务体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/P6A
- 青年职业探索的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/809=bms
- 城市生活记录的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/ipl=482
- 食品安全科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/KO2=AAD
- 数字支付体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/131
- 健康饮食教育的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/aoe
- 城市应急科普的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/LZf
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/021=pcj
- 城乡交流活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/qwv=005
- 地方戏曲体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/U86=1XV
- 老年运动活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/107
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/ryu
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/xEG
- 公园亲子设施的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/520=apm
- 城市文明出行的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/hbb=273
- 家庭照护支持的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/BpN=PJc
- 城市公共饮水的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/551
- 小区停车协商的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/ris
- 社区消防演练的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/Zzz
- 公共交通接驳的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/348=kby
- 城市农夫市集的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/spn=621
- 公共场馆服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/cOc=3A2
- 城市文明出行的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/866
- 家庭安全提示的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/dzw
- 文化场馆预约的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/TU3
- 公共空间照明的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/184=tbz
- 街区小店体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/dzd=481
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/RP4=qJk
- 学校体育活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/081
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/ofi
- 校园社团活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/6Gs
- 绿色出行服务的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/503=cjf
- 社区垃圾回收的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/krr=565
- 农村环境治理的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%9A%E5%AE%A2?/GYq=9Tj
- 数字生活课堂的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/792
- 智慧停车服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/thj
- 城乡交流活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/dfK
- 节约用水实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/938=hyd
- 社区家校合作的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/mva=418
- 社区便民集市的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/RrL=04e
- 环境监测科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/703
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/afd
- 老年友好服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/I0l
- 家庭照护支持的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/660=qfj
- 公共服务预约的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/rgx=429
- 青少年心理健康的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/O2d=oYV
- 城市雨天出行的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/462
- 低碳社区实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/ttd
- 社区体育组织的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/pbo
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/205=ovh
- 文化场馆预约的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/ubv=519
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B4%A2%E6%8A%A5?/NbK=8t3
- 日常摄影记录的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/923
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/zgr
- 城市慢行系统的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/Ga3
- 机器人科普活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/019=lda
- 基层服务创新的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ife=257
- 社区便利生活的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/t3n=30k
- 绿色校园实践的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/482
- 全民健身活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/tlp
- 急救知识普及的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/nfZ
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/115=adc
- 家庭防灾准备的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/vjl=731
- 儿童安全出行的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/WVu=h1o
- 儿童友好空间的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/859
- 科学健身方法的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/riz

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
