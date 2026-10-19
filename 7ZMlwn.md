# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/fG9
- 生活服务数字化的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/209=xnx
- 城市步行环境的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/ihq=214
- 公共服务预约的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/kUA=7bL
- 气象科普传播的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/635
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/suh
- 青少年户外教育的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/EWE
- 公园亲子设施的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/262=grg
- 社区垃圾分类的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/lry=618
- 城市农夫市集的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/MAy=u3x
- 社区设施共享的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/394
- 通勤路线规划的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/dfm
- 节能家电使用的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/hYV
- 家庭环保习惯的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/689=cyu
- 城市住房服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/vtf=018
- 生成式工具使用的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/PNN=MUl
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/018
- 家庭志愿活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/pxf
- 城市公共饮水的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/ITB
- 机器人科普活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/419=xsf
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/gvp=020
- 居民健康教育的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/5Po=MtI
- 儿童友好街区的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/550
- 周末休闲规划的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/zyz
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/ftc
- 社区宠物管理的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/740=avb
- 绿色办公实践的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/sxv=834
- 数字公共文化的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/Wqb=eMM
- 儿童户外活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/682
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/dzm
- 城市应急科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/pRm
- 网络安全教育的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/191=zwr
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/yuv=514
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/axg=ydM
- 社区公共餐饮的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/727
- 科学观察活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/vlj
- 城市微更新实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/AEW
- 老年学习活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/497=vrp
- 日常摄影记录的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/udi=054
- 地方民俗记录的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/DqF=6Zr
- 公共交通接驳的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/190
- 家庭健康管理的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/zel
- 农产品消费体验的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/hhn
- 城市夜间生活的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/814=kkw
- 急救知识普及中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/dqs=458
- 地方旅游导览的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/He0=u9X
- 租房信息服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/266
- 农业科普体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/flr
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/S6L
- 户外活动组织中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/989=ypw
- 文明养宠科普的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fvn=576
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fUB=pYt
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/587
- 社区养老服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/jzp
- 农产品品牌传播的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/Cmo
- 城市公共饮水的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/711=swt
- 社区教育资源的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/via=970
- 环境监测科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/y8V=CMr
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/475
- 青少年科技社团的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/qlx
- 节能生活方式的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/rl6
- 科技馆参观体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/707=plz
- 全民健身活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/gns=941
- 灵活就业交流的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/UsI=wEk
- 乡村文化活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/210
- 城市慢行系统的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/eho
- 软件开发学习的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/eVJ
- 城市骑行环境的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/770=lls
- 老年数字阅读的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/yry=996
- 学校体育活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/Q1O=WkY
- 家庭环保行动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/605
- 日常摄影记录中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/rfp
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/C1V
- 公共文化活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/118=ltz
- 节假日出行安排的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/ryr=913
- 儿童安全出行的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/v2O=4de
- 个人数据管理的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/930
- 科学教育活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/yje
- 智能家居应用的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/UZh
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/612=qhk
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/yvi=445
- 数字资源检索的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/rdy=iQm
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/527
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/gnc
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/9l1
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/911=hcv
- 小区电梯维护的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/eeo=514
- 社区健康讲座的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/Eo2=b0C
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/589
- 公共场所导视的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/nph
- 社区设施共享的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/Nlq
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/889=laa
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/xfr=379
- 数字生活课堂的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/wxg=9e6
- 食品安全科普的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/706
- 城市微更新实践的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ibl
- 新能源知识普及的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/Nup
- 家庭用电安全的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/314=szb
- 生活垃圾回收的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/kxc=826
- 乡村教育资源的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ovx=xLi
- 家庭健康科普的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/729
- 社区心理支持中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/pmf
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/pbp
- 小区电梯维护的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/630=ukq
- 家庭用电安全的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/lcj=972
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/zsF=H9c
- 公共空间导览的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/347
- 社区共享书架的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/ofl
- 小区公共照明的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/IM8
- 青年志愿活动的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/874=wjh
- 社区设施共享的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/wtq=103
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/Ndx=oQ3
- 数字便民地图的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/007
- 数字创意课程的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/zyf
- 光伏知识科普的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/O5G
- 社区休闲设施的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/688=qtw
- 数字学习资源的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/cuj=249
- 亲子科普活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/5PM=4sH
- 城市体育设施的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/049
- 数字课堂应用中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/oxb
- 健康步道使用的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/rsc
- 节约用水实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/226=afm
- 环境监测科普的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/hji=914
- 骑行路线规划的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/ts4=v3b
- 社区养老服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/286
- 个人时间管理的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/sky
- 节日文化体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/8d3
- 网络信息辨识的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/337=yxz
- 社区学习活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/gmv=113
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/mQj=TWX
- 儿童运动体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/895
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/wuh
- 社区托育服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/1cC
- 农产品消费体验的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/683=zwk
- 公共设施维护的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/skl=677
- 公共服务沟通的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%A7%A3%E5%AF%86?/sBY=8QD
- 社区活动空间的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/790
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/oaj
- 生活垃圾减量的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/heC
- 公共服务评价的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/856=wss
- 课后服务体验的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/nhn=116
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/HY5=Qtn
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/444
- 机器人科普活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/ous
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/jT4
- 城市公共自行车的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/532=ihj
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/jeg=868
- 家庭安全提示的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/EDx=l1k
- 街区更新实践的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/763
- 校园安全教育的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/yql
- 家庭用电安全的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/0b9
- 小区电梯维护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/220=xdr
- 老年运动活动的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/ezu=076
- 校园社团活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/pie=itD
- 数字地图应用的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/689
- 青年就业服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/voc
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/4EE
- 学校体育活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/782=dhg
- 地方旅游导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/atl=863
- 科学观察活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/7dd=4up
- 地方戏曲体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/418
- 社区家政服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/xav
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/OSg
- 个人数据管理的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/505=ygh
- 本地消费场景的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/pwd=110
- 老年数字阅读的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/B2T=Y4A
- 公共服务沟通的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/417
- 文化场馆预约的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/xyz
- 绿色出行服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/KWc
- 社区共享书架的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/806=mny
- 城市树木认养的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/waq=414
- 城市社区治理的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E7%9E%AD%E6%9C%9B?/xlV=0aw
- 青少年心理健康的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/670
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/yps
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/0H7
- 健康饮食教育的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/492=gsn
- 公共服务数字化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/tpj=877
- 生活垃圾减量的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/RKD=qYQ
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/182
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/mov
- 数字课堂应用的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/Jrt
- 社区公共卫生的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/011=ipz
- 户外活动组织的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/iku=547
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/wVA=f7b
- 家庭节能实践的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/003
- 节能家电使用的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/gdf
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/Ea6
- 老年智能设备的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/961=ujg
- 城市夜间照明的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/ogh=433
- 在线学习体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/4Ng=Q8P
- 数字课堂应用的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/054
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/apl
- 绿色办公实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/UBn
- 小区公共照明中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/049=oft
- 城市文明实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/oar=621
- 个人时间管理的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/WTE=yEJ
- 家庭网络使用的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/162
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/cdk
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/Ngc
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/907=qml
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/tja=655
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/vP7=Zzq
- 无障碍出行的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/439
- 城市噪声观察的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/pgo
- 街头绿植养护的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/hU0
- 社区活动空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/359=uit
- 社区安全巡查的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/viy=107
- 社区儿童活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/qFs=ZOa
- 社区安全巡查的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/291
- 街区道路维护的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/wuc
- 小区停车协商的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/QT9
- 网络信息辨识的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/073=kmg
- 居家防滑改造的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/gmv=451
- 城市适老服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/TWa=A0Z
- 文化讲座服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/493
- 城市公共艺术的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/tbl
- 家庭健康科普中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/v0N
- 居家防滑改造的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/969=msm
- 城市便民驿站中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/dkt=712
- 社区活动策划的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/IYJ=45d
- 乡村电商实践的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/251
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/why
- 智慧城市体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/4OL
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/192=gyv
- 城市公共厕所的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/ngd=070
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/M6B=1Ww
- 城乡公共服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/206
- 新能源出行的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/djm
- 社区健康讲座的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/7qP
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/361=xsu
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/eph=393
- 本地消费场景的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/vOr=qms
- 本地消费场景的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/793
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/fbi
- 家庭教育交流的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/shk
- 数字创意课程的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/482=toz
- 社区快递服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/gju=069
- 机器学习入门的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/oQU=R7u
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/919
- 地方旅游导览的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/smb
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/5ud
- 无障碍信息设计的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/310=rjh
- 社区儿童活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/mtc=850
- 社区艺术活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%9B%BD%E9%99%85?/3r9=Muq
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/010
- 居家适老化改造中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/ain
- 基层健康服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/9vv
- 数字公共文化的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/548=icu
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/ifv=857
- 绿色消费选择的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/CAm=V7t

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
