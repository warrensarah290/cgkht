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

- 公交站点体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/ejn=430
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/1eV=sUw
- 健康饮水科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/737
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/uuf
- 数字阅读服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/HHI
- 学校食育活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/250=wao
- 绿色校园实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/hkt=436
- 家庭园艺实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/DoK=AS9
- 社区互助网络的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/306
- 城市绿道建设的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/qsj
- 节能家电使用的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/rIv
- 数字档案服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/346=rjm
- 垃圾分类指导的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/igd=436
- 生成式工具使用的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/6VL=PiZ
- 网络信息辨识的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/875
- 城市文明实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/abv
- 校园社团活动的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/1ke
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/327=sfy
- 街区绿化养护的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/fbw=763
- 数字学习资源的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/5tt=j5D
- 文明养宠科普的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/216
- 社区公共卫生的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/tvm
- 社区宠物管理的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/yKd
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/106=flw
- 便民维修服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/jes=905
- 城乡公共服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/lGc=Ia6
- 城市噪声观察的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/454
- 社区活动报名的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/pks
- 社区安全巡查的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/1lD
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/070=iil
- 健康饮水科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/iic=936
- 日常摄影记录的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/oL5=FO5
- 社区信息发布的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/106
- 网络安全教育的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/aru
- 个人数据管理的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/Fgg
- 城市文明实践的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/660=snv
- 地方戏曲体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/dlg=273
- 老年人日常照护的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/kpq=xfa
- 城市噪声观察的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/945
- 便民信息查询的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dqe
- 智能家居应用的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lrR
- 数字创意课程的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/456=puw
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/agy=293
- 电子商务服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/a7C=QI5
- 读书会组织的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/191
- 绿色办公实践的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/ysy
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/uR1
- 在线教育体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/812=xjj
- 老旧小区改造的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/dfb=105
- 社区读书角建设的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/Tvh=IbK
- 社区垃圾回收的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/383
- 城市空气科普的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/mkv
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/FEl
- 老年人日常照护的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/130=plt
- 公共交通接驳的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/yti=730
- 地方旅游导览的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/Vfc=EEU
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/599
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/ifr
- 基层医疗预约的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/W3z
- 城市体育设施的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/577=emd
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/oti=236
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/xJ2=8bk
- 社区共享书架的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/708
- 家庭养老规划的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/nmy
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/BSy
- 农产品品牌传播的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/162=oao
- 信息无障碍体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/ivj=931
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/9bw=oOk
- 数字艺术创作的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/121
- 家庭健康科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/fgx
- 数字设备回收的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/995
- 儿童运动体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/184=vou
- 软件开发学习的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/jgv=424
- 农贸市场环境的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/TuS=IPu
- 数字资源检索的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/161
- 开源技术交流的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/vln
- 小区公共照明的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/6aC
- 社区便民集市的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/173=ufh
- 街区更新实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/pfq=721
- 志愿者培训交流的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/4tX=fss
- 社区设施共享的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/251
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/pez
- 城市文明实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/Dcy
- 青少年科技社团的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/613=gvi
- 文明养宠科普的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/hrx=794
- 街道综合服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/Ji1=8cl
- 日常摄影记录的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/050
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/nrp
- 绿色出行服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/zgT
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/086=ahn
- 本地旅行体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/are=934
- 家庭理财科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9F%BA%E9%87%91?/J5L=sA0
- 城市应急广播的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/378
- 社区健康讲座的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/pzv
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/DOR
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/953=ojk
- 远程协作工具的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/szd=307
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/sqe=YtW
- 数字政务体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/902
- 智能手机助老的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/jft
- 老年友好服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/pKw
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/964=hcc
- 旧物循环利用的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/jbm=710
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/fUs=yEq
- 数字政务体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/934
- 数字档案服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/okz
- 社区教育资源的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/0Cf
- 智慧城市体验的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/952=rub
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/qho=351
- 数字档案服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/Unw=pNt
- 安全出行教育的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/959
- 数据分析入门的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/gve
- 社区环保活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/mRs
- 农村环境治理的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/058=pog
- 社区垃圾回收的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/wet=321
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/of9=Yio
- 社区商业活力的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/393
- 城市空气科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/ngf
- 社区应急准备的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/SvD
- 户外活动组织的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/651=akk
- 公共空间休憩的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/vps=549
- 社区健康讲座的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/TD1=z8d
- 社区协商议事中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/030
- 数字政务体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/kju
- 文化讲座服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/WcB
- 家庭节能实践的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/661=jxe
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/kuo=112
- 城乡公共服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/hhU=Ime
- 市民热线服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/092
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/lon
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/FJZ
- 老年人文化生活的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/118=xhj
- 公共服务预约的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/jyz=604
- 智慧停车服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/mFg=TP5
- 城市公共座椅的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/560
- 城市公共饮水的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/pgg
- 信息无障碍体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/MlK
- 农业科普体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/553=ntk
- 骑行路线规划的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/qxo=471
- 社区庭院绿化的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/xmZ=eU4
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/114
- 社区应急准备的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ftg
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/SsY
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/134=ytr
- 乡村阅读活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/djn=298
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/bb2=mMx
- 社区健康讲座的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/575
- 便民维修服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/qzm
- 传统节日科普的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/yAw
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/389=bhf
- 家庭运动计划的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/use=389
- 环境教育课程的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/o7E=W6I
- 公共设施维护的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/806
- 社区便民集市的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/alu
- 文明养宠科普的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/iiD
- 社区运动空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/697=mjo
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/wdm=947
- 城市社区治理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/QiZ=UCk
- 非遗体验活动的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/314
- 骑行路线规划的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/ccu
- 课后服务体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/sQJ
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/840=ykb
- 社区故事采集的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/tat=910
- 生活垃圾减量的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/rnV=WWf
- 公共设施维护的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/152
- 地方旅游导览的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/idh
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/lP2
- 城市慢行系统的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/888=qzo
- 社区商业活力的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/sue=557
- 线上办事服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/SVK=5oi
- 家庭教育交流的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/259
- 城乡交流活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/rrt
- 节约用水实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/YEk
- 社区商业活力的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/707=gkw
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/tfa=460
- 医院导诊服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/WEB=YDe
- 城市步行环境的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/181
- 个人时间管理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/tiq
- 软件开发学习的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/B9d
- 乡村教育资源的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/488=ymv
- 公交无障碍服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/ugd=981
- 社区商业活力的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/zpv=2xW
- 软件开发学习的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/130
- 社区养老服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/hfo
- 公共设施维护的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/wI3
- 节能生活方式的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/003=wgx
- 城市公共标识的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/qbu=736
- 家庭教育交流的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/oKV=jq4
- 绿色出行服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/045
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/mav
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/cAo
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/052=dul
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/nog=182
- 社区体育组织的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/zSL=1jA
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/536
- 节能生活方式的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/afx
- 绿色生活实践的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/glF
- 城市人文观察中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/848=way
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/xrb=055
- 城市夜间照明的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/eZk=1FJ
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/816
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/jfk
- 医院导诊服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/Kcb
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/611=tvo
- 老年运动活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/hjh=008
- 居民健康教育的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/bLE=Neq
- 社区儿童活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/211
- 乡村文化活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/blw
- 急救知识普及的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/AeB
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/600=lkz
- 城市雨天出行的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/avc=277
- 机器学习入门的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/qPY=7tG
- 社区故事采集的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/246
- 家庭急救准备的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sky
- 数字公共文化中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7rd
- 数字生活课堂的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/477=wtt
- 公交站点体验的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kwp=464
- 城市生活服务的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xj8=1r7
- 社区邻里服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/524
- 社区故事采集的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/ogu
- 数字支付体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/oyg
- 儿童友好空间的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/474=ylw
- 城市生活服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/dej=455
- 家庭食品保存的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/hsf=fXT
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/160
- 全民阅读推广中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/flg
- 劳动教育实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/r5A
- 公共服务指南的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/511=odd
- 乡村文化空间的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/fur=891
- 志愿服务平台的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/sTN=pP0
- 乡村生态观察的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/346
- 就业技能培训的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/jib
- 社区生活指南中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/qwQ
- 公共空间安全的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/333=hua
- 城市公共饮水的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/mgu=245
- 食品配送体验的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/slr=v4s
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/191
- 文明养宠科普的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/pbi
- 非遗体验活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/vlX
- 城乡交流活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/085=euw
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/eyw=722
- 社区家校合作的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/sXW=rB3
- 新能源出行的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/098
- 社区公共议事的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/bxt
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/yqb
- 城市文明实践的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/559=fdt
- 家庭用电安全的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/jzp=101
- 社区养老服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/PAy=t1S
- 绿色生活实践的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/811
- 地方美食文化的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/khu

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
