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

- 城市步行环境的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/478
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/dtn
- 乡村公共服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/qS0
- 城市绿色交通的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/150=icr
- 全民阅读推广的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/pgs=444
- 数字资源检索的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/Dz4=T3p
- 通勤路线规划的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/261
- 城市公共标识的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/war
- 乡村文化空间的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/mkM
- 城市文明实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/719=yes
- 城市文化路线的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/vbo=566
- 便民信息查询的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/70U=TmF
- 城市公共饮水的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/476
- 小微企业服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/mgg
- 家庭安全提示的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/lDG
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/681=qxk
- 数字生活课堂的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/dwc=952
- 数字生活课堂的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/4EI=xFv
- 电动汽车充电的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/595
- 家庭志愿活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/ovg
- 传统节日科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/nhP
- 城市慢行系统的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/860=xam
- 家庭科学教育的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/jdy=618
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/nh9=VwH
- 社区环保活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/020
- 应急物资管理的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/oov
- 老年人出行服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/Ebn
- 市民热线服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/968=oyf
- 电动汽车充电的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/jvr=228
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/8I1=ar3
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/309
- 社区活动空间的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/cwf
- 基层健康档案中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/5iY
- 家庭消费规划的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/109=aia
- 安全出行教育的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/iby=081
- 口袋公园建设的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/200=WUF
- 传统节日科普的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/474
- 城市噪声观察的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/gef
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/OLb
- 公共服务指南的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/806=luy
- 家庭园艺实践的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/bxr=170
- 环境监测科普的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/pu0=i0d
- 校园安全教育的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/740
- 城市噪声观察的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/asr
- 数字课堂应用的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/y5w
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/814=vfa
- 城市文明实践的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/rcs=844
- 家庭消费规划的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/tit=c6z
- 家庭收纳实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/154
- 便民服务窗口的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/swm
- 家庭用电安全的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/16L
- 街区更新实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/876=vty
- 个人数据管理的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/kpy=683
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/I2F=eMz
- 儿童运动体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/662
- 城市绿道建设的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/zdp
- 公共服务咨询的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/eOf
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/027=qyp
- 读书会组织的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/xqp=914
- 数字学习资源的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/0Pb=PaK
- 校园社团活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/123
- 生活垃圾回收的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/xvh
- 数字支付体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/Ers
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/941=xdc
- 校园社团活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/tvh=498
- 校园社团活动的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E9%97%AE%E7%AD%94?/FLQ=1zs
- 社区故事采集的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/207
- 城乡交流活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/pdd
- 公共交通接驳的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/3a2
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/076=uyw
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/bou=542
- 全民阅读推广的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/RTQ=xDv
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/922
- 急救知识普及的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/krh
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/tEd
- 家庭理财科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/063=azl
- 公共服务评价的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/jix=060
- 物业服务沟通的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/bMz=zJe
- 城市文化路线的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/470
- 小微企业服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/xam
- 绿色校园实践的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/Imo
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/958=uzm
- 就业技能培训的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/bob=195
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/laD=nul
- 城市雨天出行的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/369
- 城乡公共服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/fdv
- 社区家校合作的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/GKP
- 校园阅读活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/911=deo
- 社区家校合作的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/tai=654
- 社区知识分享的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/L20=qPP
- 生成式工具使用的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/162
- 节能生活方式的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/wyc
- 社区庭院绿化的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/kxh
- 数字设备回收的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/409=own
- 城市微更新实践的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/ldd=824
- 节假日出行安排中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/bLL=6FD
- 居家防滑改造的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/175
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/qjt
- 基层服务创新中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/Vst
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/369=vsu
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/urd=673
- 非遗体验活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/LqU=BEt
- 小微企业服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/291
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/cnc
- 家庭健康管理的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/2T2
- 便民维修服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/353=dpx
- 学校体育活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/bjk=158
- 电子商务服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/KRL=OVl
- 校园节能行动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/599
- 社区健康讲座的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/xpc
- 公共服务预约的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/nhF
- 光伏知识科普的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/090=pnp
- 农村环境治理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/vtu=383
- 城市公共空间的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/Hea=6t8
- 家庭环保行动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/344
- 城市公共座椅的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/fvy
- 环境教育课程的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/rDJ
- 乡村公共文化的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/232=uuy
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/yex=692
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/ptv=YpK
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/001
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/bvr
- 街头绿植养护的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/5Me
- 智慧停车服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/157=cis
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/ufq=929
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/ATG=dPy
- 社区菜市场服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/127
- 通勤路线规划的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/ukq
- 读书会组织的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/AdK
- 社区垃圾回收的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/423=jhs
- 数字政务体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/ztv=592
- 医院导诊服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/Zir=nV5
- 读书会组织从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/785
- 公共服务指南的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/acr
- 公共场所导视的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/gV8
- 非遗体验活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/324=urq
- 开放式学习空间的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/vzw=222
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/3yt=Me9
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/539
- 城市骑行环境的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/xpu
- 老年人文化生活的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/cU9
- 城市骑行环境的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/644=tan
- 个人信息保护的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/uqc=621
- 小区公共照明的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E5%86%9B%E4%BA%8B?/8W5=ZWc
- 社区教育资源的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/723
- 家庭阅读计划的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/koq
- 食品配送体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/ieZ
- 科学健身方法的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/082=fbc
- 城市空气科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/mlo=264
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/HUO=roU
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/482
- 便民维修服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/vlc
- 应急物资管理的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/odV
- 社区体育组织的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/590=qxo
- 乡村产业科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/njb=990
- 老年学习活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/rUn=sbf
- 家庭运动计划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/209
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/azv
- 青少年科技社团的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/VmD
- 户外活动组织的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/439=wij
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/hhe=130
- 社区庭院绿化的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/ewi=FNU
- 城市树木认养的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/399
- 低碳社区实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/wjs
- 光伏知识科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/0kd
- 周末休闲规划的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/651=jhn
- 便民维修服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/cnw=936
- 街区更新实践的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/fIK=mis
- 科学信息获取的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/427
- 数字支付体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/hny
- 公共空间导览的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/QB3
- 街区更新实践的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/618=wpq
- 公共卫生设施的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/znx=322
- 地方民俗记录的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/JkP=Yit
- 急救知识普及的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/583
- 社区知识分享的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/tza
- 环境教育课程的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/QNJ
- 社区活动策划的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/025=eqz
- 社区生活指南的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/thr=866
- 社区商业活力的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/ti7=CJa
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/129
- 社区文化传播的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/scq
- 社区读书角建设的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/UEW
- 信息无障碍体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/202=vfk
- 网络安全教育中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/mkx=055
- 劳动教育实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9A%E4%BF%A1?/it8=NZ9
- 地方戏曲体验的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/681
- 城市休闲步道中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/rsz
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/9iw
- 城市树木认养的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/256=lcz
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/ldk=798
- 城乡交流活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/DBe=wEy
- 小区停车协商的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/487
- 社区便利生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/wvk
- 公共场所导视的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/IUS
- 垃圾分类指导的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/158=fyf
- 图书借阅体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/olg=259
- 城市噪声观察的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/NHZ=q19
- 乡村电商实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/517
- 乡村文化活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/ghb
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/W6I
- 城市微更新实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/719=kbz
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/qqw=428
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/6L6=pj0
- 线上办事服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/272
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/ysn
- 科技馆参观体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/fHc
- 公园无障碍服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/972=edp
- 机器人科普活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/suz=258
- 社区生活指南的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%B8%B8%E6%88%8F?/qlI=JCl
- 口袋公园建设的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/070
- 节能家电使用中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/nsh
- 公共交通信息服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/9Tm
- 绿色出行服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/739=dty
- 老年运动活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/qpk=401
- 社区活动报名的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/DA2=iNT
- 街区小店体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/585
- 医院导诊服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/dyc
- 城市便民驿站中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/37X
- 人工智能科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/528=phk
- 社区体育组织的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/jps=871
- 社区活动策划的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/MqH=Lrv
- 乡村公共阅读的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/824
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/snj
- 社区家政服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/2Eg
- 节能家电使用的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/961=ygi
- 社区体育组织的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/zrj=430
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/maU=S2z
- 城乡交流活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/362
- 基层健康档案的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/hwt
- 城市可持续生活的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/RSr
- 家庭养老规划的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/735=nyi
- 数字资源检索的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/jwd=009
- 本地历史资料的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/12p=bIE
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/794
- 开放式学习空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/fos
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/CL2
- 公共服务评价的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/051=ibh
- 在线学习体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/uhx=149
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/pyG=DKF
- 社区环保活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/745
- 城市运动公园的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/nkw
- 节能家电使用的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/51C
- 社区艺术活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/995=wuq
- 社区活动报名的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/kgc=191
- 社区邻里服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/Egc=uGG
- 社区阅读服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/082
- 青少年户外教育的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/uwo
- 社区商业活力的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/2rF
- 儿童阅读角的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/224=kch

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
