# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 读书会组织的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/118
- 公共服务预约的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/wto
- 农村环境治理的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/o3j
- 健康饮水科普的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/059=khz
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/upq=000
- 网络信息辨识的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/rdX=nnp
- 社区读书角建设的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/572
- 急救知识普及的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/vks
- 公交站点体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/tMb
- 社区家政服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/992=obo
- 亲子科普活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/qne=065
- 非遗体验活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_85%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/wHM=tak
- 科学健身方法的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/656
- 校园社团活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/nrk
- 数字课堂应用的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/NIt
- 无障碍信息设计的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/514=hkn
- 青少年科技社团的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/xgl=024
- 基层健康档案的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A83d%E5%9B%BE%E5%BA%93%E8%93%9D%E7%B2%BE%E7%81%B5_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/9mF=2rN
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/353
- 老年智能设备中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/rrj
- 公共服务预约的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/ZvK
- 城市应急科普的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/122=trv
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/euy=721
- 社区菜市场服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A985%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/WO3=2iA
- 乡村生活观察的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/544
- 数字课堂应用的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/viy
- 小微企业服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/3Ef
- 社区便民集市的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/911=iab
- 学校体育活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/alf=566
- 社区活动空间的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/Ge3=sOH
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/925
- 社区交通安全的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mqo
- 社区花园共建的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/eqo
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/362=leu
- 数字地图应用的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bis=724
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_937%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mU7=WZU
- 家庭食品保存的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/885
- 绿色办公实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/jly
- 城乡公共服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/GCk
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/667=suz
- 开源技术交流的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/mct=838
- 公共服务咨询的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988CC1_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/o3c=QFd
- 城市基础设施的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/669
- 安全出行教育的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/hbm
- 青少年户外教育的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/gQb
- 智能家居应用的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/049=hmy
- 机器人科普活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/gwt=185
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/o4v=wVg
- 城市住房服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/056
- 线上阅读资源的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/vzs
- 社区邻里服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/iVx
- 街道综合服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/026=cag
- 农产品消费体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/fpm=655
- 就业技能培训的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_988cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/HxX=aAG
- 社区应急准备的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/134
- 公园休闲体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/mwc
- 个人时间管理的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/jF1
- 在线学习体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/547=mji
- 远程协作工具的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/bqp=563
- 志愿者培训交流的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/dpY=ZBU
- 家庭食品保存的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/673
- 社区宠物管理的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/cmu
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/6Vs
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/377=jnn
- 个人信息保护的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/ytw=141
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/FQP=T5d
- 健康信息获取的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/813
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/lvc
- 数字阅读服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/osA
- 数字艺术创作的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/206=iyk
- 社区信息发布的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/icv=688
- 公园亲子设施的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/KHX=b6f
- 电动汽车充电的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/723
- 公益活动组织中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/yrr
- 家庭园艺实践的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/yDb
- 公共设施维护的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/940=atj
- 数字艺术创作的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/gxa=538
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E5%85%AC%E5%BC%80%E8%AF%BE?/SUd=LJ0
- 社区便民服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/811
- 非遗课堂体验的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/rfw
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/fxC
- 读书会组织的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/892=hsz
- 公交无障碍服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/hlp=447
- 社区活动空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/HBz=DJw
- 公共服务咨询的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/753
- 公共文化活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/igo
- 家庭照护支持中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/MyG
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/978=wpg
- 社区便利生活的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/rsg=749
- 街区小店体验的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_985%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/osL=R02
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/545
- 科技馆参观体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/hmb
- 城市适老服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/wmQ
- 社区公共卫生的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/068=qpp
- 公园无障碍服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/miz=263
- 城市雨天出行的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_567cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_360%E8%BF%B0%E8%AF%84?/msH=uB5
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/198
- 社区互助网络的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/sku
- 绿色校园实践的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/TCJ
- 社区运动空间的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/278=wym
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/wfb=631
- 志愿者培训交流的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2123cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/O9t=J50
- 社区应急准备的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/941
- 公共空间导览的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/cxt
- 儿童运动体验的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/ru0
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/973=byt
- 城市公共空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/dxt=675
- 创业经验分享的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_2123-cc%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/eOC=gF7
- 垃圾分类指导的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/634
- 社区家校合作的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/lwv
- 社会体育指导的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/9c1
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/308=dpu
- 社区家校合作的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/pvt=846
- 数字政务体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_2123cc%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/0xg=48T
- 节气饮食文化的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/678
- 社区知识分享的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/rxj
- 社区家政服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/4b7
- 远程协作工具的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/444=hxf
- 家庭安全提示的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/bex=520
- 社区设施共享的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_2123cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/YVf=AZ3
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/134
- 环境监测科普的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/bpx
- 安全出行教育的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/mKg
- 在线教育体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/332=wxn
- 食品安全科普的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/tsb=252
- 老年智能设备的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_2123cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/Qpq=v55
- 城市公共艺术的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/078
- 电子商务服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/lqu
- 社区活动策划的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/X4k
- 青年就业服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/072=lgt
- 绿色消费选择的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/gza=787
- 城市共享单车的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_www.2123.cc_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/DRo=xZ9
- 社区老年食堂的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/010
- 社区垃圾分类的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/uzk
- 社区教育资源的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/ZaN
- 线上办事服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/772=vyl
- 社区花园共建中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/fbd=849
- 老年人日常照护的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/RCB=28t
- 社区安全巡查的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/391
- 儿童安全出行的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/vdz
- 城市基础设施的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/I6y
- 社区停车服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/924=xlb
- 社区养老服务的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jub=034
- 校园阅读活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/IAt=Kox
- 健康饮水科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/810
- 城市应急科普的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/flv
- 气象科普传播的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/8to
- 数字档案服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/069=ccr
- 城市骑行环境的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/xhf=878
- 家庭饮食安排的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360?/kss=Au3
- 城市应急广播的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/118
- 网络信息辨识的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/qdj
- 城市雨天出行的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/pwX
- 家庭网络使用的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/231=ehv
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/pri=423
- 网络信息辨识的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8818cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E6%A6%9C%E5%8D%95?/dvk=Wvd
- 数字学习资源的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/145
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/sgp
- 社区文化传播的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/0tf
- 社区艺术活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/552=viw
- 农产品品牌传播的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/hrs=107
- 健康饮水科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8.CC_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/TBp=L8u
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/348
- 基层服务创新的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/etm
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/tO7
- 家庭节能实践的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/413=rrj
- 就业技能培训的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/kko=941
- 城市噪声观察的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_8818cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/iaL=U06
- 生活服务数字化的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/247
- 公共文化活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/pck
- 科技馆参观体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/v89
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/664=xim
- 城市文明出行的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/sws=841
- 家庭健康管理的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_8818cc%E5%BD%A9%E7%A5%A8ios_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/Nfq=3Ix
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/710
- 城市展览体验的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/hzc
- 科学运动指导的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/Ujr
- 乡村文化空间的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/203=igx
- 数字创意课程的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/pyk=845
- 节假日出行安排的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1588%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/AAp=D3f
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/667
- 通勤路线规划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/fev
- 乡村教育资源中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/XZT
- 城市展览体验中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/422=xtp
- 家庭网络使用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/ghi=500
- 城市地名文化的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1588cc%E6%B8%AF%E6%BE%B3%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/aqy=al7
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/845
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/sgz
- 社区花园共建的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/6vS
- 社区体育组织的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/146=noo
- 公共设施使用的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/clr=389
- 城市应急科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_1588cc%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/Nyl=2Tm
- 城市绿道建设的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/162
- 开放式学习空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/ing
- 家庭志愿活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/9Li
- 城市便民驿站的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/004=zpr
- 口袋公园建设的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/lqt=095
- 社区托育服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_210cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/Vp9=gRj
- 科学观察活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/811
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/cvh
- 社区消防演练的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/x92
- 休闲运动入门的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/280=utl
- 城市噪声观察的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/jht=701
- 校园安全教育的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_210cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/aYI=GyI
- 公共服务指南的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/857
- 公交站点体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/lgq
- 健康步道使用的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/LcE
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/261=did
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/veg=573
- 城市生活服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/L5W=WwB
- 社区便民集市的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/845
- 新能源出行中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/csl
- 人工智能科普的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/Z5X
- 生成式工具使用的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/804=cqt
- 社区文化节活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/udk=165
- 社区家政服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_210cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/fYX=Z45
- 城市公共厕所中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/189
- 公共空间照明的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/sgv
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/Jal
- 公共服务评价的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/342=nxo
- 在线教育体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/tuc=721
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/ucn=HdQ
- 本地历史资料的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/446
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/oig
- 社区志愿服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/lza
- 运动安全知识的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/070=cvh
- 个人信息保护的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/uno=129
- 社区垃圾回收的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%8A%A8%E6%BC%AB?/BVn=Fhj
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/838
- 生活技能分享的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/sfd
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/hj5
- 基层健康档案的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/613=wlv
- 老年运动活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/vue=504
- 终身学习资源的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B9%A6%E7%94%BB?/9wY=Har
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/557
- 城市便民驿站的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/xih
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/Fe7
- 节能家电使用的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/798=zbj
- 城市人文观察的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/mbt=744
- 社区协商议事的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_831cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/kY7=PQt
- 数字学习资源的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/172
- 城市慢跑路线的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/kxj
- 社区学习活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/EV4
- 城市树木认养的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/076=xmd
- 城市夜间生活的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/fgs=577
- 城市步行友好的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_831cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/kbk=S3x
- 校园安全教育的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/369
- 家庭科学教育的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/aga
- 街区小店体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/YLK
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/682=qyd

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
