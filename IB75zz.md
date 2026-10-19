# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 公共健身器材的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/cle=493
- 社区生活指南的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/DBa=TVh
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/670
- 家庭安全提示的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/hyq
- 社区体育组织的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/w2O
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/825=vwd
- 数字创作工具的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/ykq=643
- 口袋公园建设的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/9SC=Fxh
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/957
- 社区修缮行动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/ixp
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/Y9h
- 城市微更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/553=jyz
- 环境教育课程的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/fsh=038
- 城市公共标识的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/gss=Toh
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/413
- 网络信息辨识的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/owi
- 家庭网络使用中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/gWQ
- 社区邻里服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/083=lpj
- 地方旅游导览的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/yfy=851
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/GzY=ssE
- 城市慢行系统的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/594
- 公共文化活动的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lzf
- 社区学习活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/MMj
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/035=pux
- 青少年编程学习的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/kvj=354
- 邻里共享空间的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/GxO=uMV
- 儿童友好空间的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/364
- 城市公共饮水的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/exo
- 急救知识普及的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/BLH
- 线上阅读资源的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/098=tmy
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/atv=992
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A?/rn8=UJq
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/703
- 文化场馆预约的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/mcy
- 数字创作工具的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Vwg
- 创业经验分享的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/552=sxg
- 地方文化传播的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/kan=116
- 邻里共享空间的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/dmv=r5i
- 小区公共照明的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/834
- 青年志愿活动的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/mei
- 家庭科学教育的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/VAH
- 城市便民驿站的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/565=nxp
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/hvw=068
- 公交站点体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/XrD=ttG
- 社区托育服务的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/707
- 社区法律科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/wrv
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/Wn3
- 智能家居应用的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/733=taj
- 乡村文化空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/gzp=252
- 地方戏曲体验的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/SoA=4UA
- 绿色生活实践的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/443
- 食品安全科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/txh
- 生成式工具使用的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/UjU
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/573=cfq
- 家庭科学教育的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/kgn=493
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/Hik=DDt
- 公共服务数字化的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/878
- 小微企业服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/qaf
- 课后服务体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/4kK
- 社区宠物管理的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/414=gvj
- 社区环保活动的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/dfy=677
- 老年人出行服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8A%A8%E6%BC%AB?/Ltx=mi5
- 通勤路线规划的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/450
- 数字创意课程的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/oqf
- 社区家校合作的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/9Xd
- 家庭节能实践的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/704=bgs
- 乡村公共文化中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/iqi=042
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/vMp=fMu
- 社区手工活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/682
- 通勤路线规划的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/bqj
- 公共空间休憩的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/rC2
- 城市文明实践的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/470=clp
- 家庭健康管理的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/jbw=099
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/TLf=cXS
- 数字支付体验的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/592
- 城市建设科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/qdc
- 乡村文化空间的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/TOy
- 社区读书角建设的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/024=ane
- 口袋公园建设的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/gro=891
- 儿童运动体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/624=XsT
- 数字素养提升的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/967
- 城市绿色交通的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/bqu
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/xrx
- 电动汽车充电的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/036=xhi
- 城市慢行系统的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/bxw=041
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/aIf=4t5
- 旧物循环利用的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/064
- 机器学习入门的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/cuv
- 城市博物馆服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/1ug
- 城市步行友好的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/157=gzz
- 家庭照护支持的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/quk=682
- 青少年心理健康的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/lyT=MuC
- 节约用水实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/620
- 公共空间照明的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/djj
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/aqE
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/444=yjz
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/fay=184
- 数字生活课堂中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/ePr=0nl
- 电子商务服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/980
- 小微企业服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/fkx
- 绿色生活实践的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/gKS
- 科学健身方法的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/512=ugr
- 便民信息查询的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/kye=999
- 绿色办公实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/Vjs=IYZ
- 青少年科技社团的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/541
- 街区绿化养护的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/amx
- 便民维修服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/j9D
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/966=wjv
- 智慧城市体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/ewf=772
- 图书馆数字服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/tZs=ydh
- 网络安全教育的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/896
- 儿童友好街区的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/hsu
- 科学观察活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/34Z
- 乡村公共文化的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/959=lkk
- 科技馆参观体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/lcy=999
- 城乡公共服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_168%E9%A3%9E%E8%89%878%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/Y7o=vJL
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/927
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/jdk
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/mmw
- 人工智能科普的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/638=zme
- 社区活动报名的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/qio=770
- 本地消费场景的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/pej=IMo
- 家庭健康管理的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/453
- 家庭阅读计划的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/tef
- 公共交通接驳的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/KrN
- 地方文化传播的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/659=zht
- 社区体育组织的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/xec=479
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/o8s=IN3
- 社区活动策划的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/491
- 家庭节能实践的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/jvw
- 个人信息保护的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/Idy
- 城市夜间生活的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/504=adi
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/emc=720
- 家庭消费规划的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/1nM=ZM7
- 市民热线服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/824
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/ojp
- 青年职业探索的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/eQN
- 科学信息获取的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/469=qvc
- 职业技能学习的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/nih=214
- 家庭节能设备中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/mRT=xXm
- 居民健康教育的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/623
- 基层健康档案的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/dvv
- 家庭养老规划的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/rkU
- 基层健康档案的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/779=ngo
- 乡村公共文化中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/akn=068
- 城市可持续生活的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E4%B9%B0%E6%B3%95%E6%8A%80%E5%B7%A7_360%E6%A1%A3%E6%A1%88?/QQE=puD
- 文化讲座服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/955
- 线上办事服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/kck
- 青少年科技社团的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/kWn
- 社区便民服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/958=wre
- 公共空间照明的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/ghp=165
- 城市建设科普的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/me6=8Dh
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/192
- 社区邻里服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/eoz
- 青少年科技社团的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/xjE
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/315=gve
- 创业经验分享中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/vkx=028
- 社区学习活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/mYo=Uwc
- 社区停车服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/945
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/zmv
- 地方文化传播的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/Yk8
- 线上办事服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/286=yrr
- 儿童安全出行的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/grd=131
- 社区商业活力的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%BF%AB%E6%8A%A5?/16c=7le
- 开源技术交流的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/210
- 科学信息获取的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/sop
- 社区儿童活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/Zmd
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/993=nwt
- 数字档案服务的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/ymi=312
- 节能生活方式的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E9%A1%B5%E7%89%88_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/lIl=ZN3
- 社区健康讲座的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/747
- 市民意见收集的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/mtj
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/FDJ
- 急救知识普及的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/909=juf
- 灵活就业交流的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/vnq=756
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/09o=Ief
- 城市生活服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/385
- 公园休闲体验的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/his
- 家庭防灾准备的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/zzv
- 家庭网络使用的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/993=wbd
- 社区心理支持的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/qdh=558
- 社区故事采集的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/jr5=Z4c
- 社区便利生活的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/388
- 社区阅读服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mit
- 公共服务咨询的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Sc8
- 家庭教育交流的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/581=ivf
- 老年数字阅读的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/zng=409
- 社区信息发布的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/lIF=WXw
- 城市文明出行的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/212
- 城市公共自行车的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/bbf
- 数据分析入门中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/Xmo
- 社区教育资源的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/519=tsh
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/vhy=473
- 家庭消费规划的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96app_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/rHN=tOa
- 社区体育组织的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/880
- 在线学习体验的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/pbp
- 家庭防灾准备的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/wUS
- 网络信息辨识的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/991=yrq
- 社区体育组织的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/unc=045
- 个人数据管理的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8app_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/fv2=Qyl
- 乡村产业科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/603
- 城市公共饮水的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/aeo
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/2me
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/710=tco
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/fqg=827
- 农村环境治理的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/7Un=T8b
- 数字阅读服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/527
- 地方旅游导览的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/xoc
- 家庭安全提示的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/4hq
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/033=bix
- 老年数字阅读的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/pif=493
- 电子商务服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87app_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/7SV=u4d
- 社区便民集市的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/353
- 城市步行环境的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/xrp
- 家庭食品保存的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/Vj3
- 终身学习资源的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/833=are
- 开源技术交流的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/fjv=450
- 乡村文化空间的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/2an=Q13
- 公共设施使用的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/388
- 乡村产业科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/eev
- 乡村公共阅读的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/Tre
- 灵活就业交流的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/939=lat
- 家庭节能实践的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/pzn=639
- 数字档案服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/lMh=lQK
- 旧物循环利用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/553
- 健康步道使用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/gro
- 家庭科学教育中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/PoR
- 科学信息获取的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/584=djs
- 科技馆参观体验的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/gfc=432
- 公交无障碍服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A67%E7%A0%81%E8%AE%A1%E5%88%92%E5%BF%83%E5%BE%97_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/Mla=rsJ
- 文明养宠科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/563
- 老旧小区改造的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/vuf
- 乡村公共服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/4mv
- 城市微更新实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/251=shz
- 农贸市场环境的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/qjs=456
- 日常摄影记录的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BE%8E%E5%A6%86?/TIt=ihV
- 节能家电使用的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/926
- 线上阅读资源的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/tyg
- 社区共享书架的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/JO3
- 农村环境治理的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/674=twh
- 城市绿色交通的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/hzw=595
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86PK10_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/sU6=Vjk
- 本地消费场景的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/307
- 社区防暑服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mkc
- 公共文化活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/hQm
- 城市可持续生活的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/927=pbz
- 社区协商议事中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/wlp=312
- 城市应急广播的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E8%B5%9B%E8%BD%A6_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Mhg=POv
- 城市生活服务的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E7%9A%84%E6%9C%BA%E4%BC%9A%E5%A4%A7_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/500
- 城市文化路线的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E7%9A%84%E6%9C%BA%E4%BC%9A%E5%A4%A7_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/ouy

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
