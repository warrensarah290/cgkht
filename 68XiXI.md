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

- 公共场所导视的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/601
- 城市基础设施的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/fwc
- 读书会组织的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/MVO
- 口袋公园建设的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/492=kkb
- 社区学习活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/zdz=044
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/onx=SPH
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/063
- 城市可持续生活的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/agu
- 家庭饮食安排的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/eb4
- 旧物循环利用的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/150=uet
- 社区垃圾分类的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/gss=510
- 公共服务咨询的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/uaA=rSY
- 全民健身活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/741
- 乡村公共阅读的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/oxt
- 旧物循环利用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/FKk
- 社区便利生活的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/998=ojt
- 健康步道使用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/scg=368
- 气象科普传播的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/PiU=BF0
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/937
- 城乡交流活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/dfu
- 社区公共餐饮的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/DQR
- 生活垃圾减量的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/709=vqy
- 数字设备回收的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/rno=508
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/ePG=Go1
- 公共卫生宣传的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/088
- 新能源知识普及的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/xwj
- 城市夜间生活的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/Afk
- 老年人日常照护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/011=nri
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/qbp=510
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/nXd=uK0
- 城市文化路线的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/630
- 家庭饮食安排的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/wou
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/TMG
- 公共设施维护的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/786=ejh
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/mft=129
- 社区科普课堂的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E6%8A%A5?/7vb=E5K
- 公交站点体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/369
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/hua
- 社区家校合作的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/EFd
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/084=mrx
- 电子商务服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/byx=762
- 家庭收纳实践的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/LbO=EO8
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/069
- 非遗体验活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/fha
- 垃圾分类指导的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/6Fs
- 课后服务体验的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/897=hhy
- 基层健康服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/mbi=541
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/6Ri=HVg
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/825
- 城市基础设施的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/veh
- 城市夜间照明的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/mTc
- 便民信息查询的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/369=kyy
- 智能家居应用的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/fle=525
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/gkx=Cwb
- 社区停车服务的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/269
- 城乡公共服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/leo
- 家庭安全提示的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/YcT
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/256=sin
- 社区菜市场服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/abu=423
- 科学教育活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/vt1=bv7
- 社区垃圾回收的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/733
- 社区文化传播的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/tlr
- 城市基础设施的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/TJ1
- 城市游园体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/160=djm
- 乡村电商实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/xok=909
- 儿童运动体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/FlT=lrB
- 数字艺术创作的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/405
- 市民热线服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/fae
- 社区交通安全的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/4DI
- 老年数字阅读的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/356=aye
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ezs=311
- 运动安全知识的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/45p=juI
- 社区读书角建设的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/894
- 老年学习活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/rgk
- 社区健康讲座的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/Si4
- 社区活动空间的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/508=mxa
- 数字支付体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/nax=681
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/AX4=eDo
- 基层医疗预约的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/569
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/iuu
- 社区环保活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/fOb
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/975=tuf
- 公共服务沟通的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/woz=102
- 日常摄影记录的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/stK=Gyx
- 市民热线服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/994
- 电子商务服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/jhr
- 环境监测科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/6gI
- 公共服务评价的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/027=gow
- 公共图书馆服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/bmr=594
- 全民阅读推广的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/egD=8nC
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/552
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/fiz
- 农贸市场环境的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/I04
- 读书会组织的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/048=heg
- 网络信息辨识的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/uzi=272
- 家庭运动计划的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/IdW=b9a
- 社区艺术活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/061
- 图书借阅体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/qpb
- 公共场所导视的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/GZE
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/387=opg
- 社区设施共享的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/ang=104
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%8A%95%E8%B5%84?/IRr=J6z
- 城市基础设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/866
- 志愿服务平台的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/jbu
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/iUx
- 青少年编程学习的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/704=emv
- 老年人出行服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/gpm=923
- 城市步行环境的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/zO4=Vjx
- 生活服务数字化的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/589
- 数字公共文化的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/ufi
- 节能生活方式的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/0PF
- 小区停车协商的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/507=vav
- 社区信息发布中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/pem=848
- 便民维修服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/zbQ=MwX
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/958
- 校园节能行动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/kqx
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/sgq
- 公共服务预约的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/929=pbi
- 社区交通安全的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/ayo=275
- 社区学习活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/LrN=BzR
- 绿色校园实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/937
- 社区菜市场服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/gmg
- 城市步行友好的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ljG
- 社区环保活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/577=bmk
- 数字创作工具的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/pca=615
- 家庭收纳实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/0vi=TdM
- 农产品消费体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/399
- 城乡交流活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/kki
- 科普展览体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/h4K
- 城市夜间照明中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/574=peh
- 社区商业活力的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/jeb=467
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP_360%E7%BE%8E%E5%A6%86?/Ujk=dPp
- 城市共享单车的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/468
- 社区便民集市的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/dfn
- 公交站点体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/lv0
- 街头绿植养护的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/643=cya
- 物业服务沟通的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/fyr=803
- 科学运动指导的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%BB%8F%E6%B5%8E?/YBr=54Y
- 城市建设科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/808
- 家庭节能实践的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/gre
- 城市绿道建设的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/371
- 公交站点体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/521=bzs
- 节假日出行安排的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/crr=784
- 老年人日常照护的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/kys=Skq
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/991
- 社区心理支持的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/vgl
- 城市应急科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/UzX
- 科学观察活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/864=gaw
- 口袋公园建设的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/ibf=516
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/QEd=8kp
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/800
- 志愿服务平台的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/hvp
- 城市公共座椅的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/zWm
- 周末休闲规划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/201=plz
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/uus=854
- 家庭网络使用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%80%BA%E5%B8%82?/ius=pWa
- 公共交通接驳的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/420
- 社区便民集市的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/zkh
- 节假日出行安排的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/9tB
- 科普展览体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/218=hhw
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/wop=332
- 骑行路线规划的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/rFY=ztH
- 机器人科普活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/275
- 节气饮食文化的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/dam
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/8lS
- 社区慢性病防控的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/727=qzp
- 家庭消费规划的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/tqf=480
- 传统节日科普的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/UDH=Wng
- 城市应急广播的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/824
- 城市生活记录的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/rxl
- 家庭园艺实践的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/780
- 医院导诊服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/371=ejr
- 灵活就业交流的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/ytn=445
- 劳动教育实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/mU8=y4a
- 城市公共标识的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/823
- 儿童户外活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/fov
- 社区托育服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/MBg
- 社区公共卫生的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/168=jxu
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/rsj=809
- 老年人文化生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/Qa7=W7K
- 老年数字阅读的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/908
- 城市共享单车的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/luf
- 城市体育设施的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/BeG
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/565=qdh
- 社区养老服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/lgu=653
- 家庭安全提示的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/zMD=9Bo
- 公共服务指南的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/155
- 公共空间照明的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/pbj
- 科学运动指导的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/PDQ
- 老年运动活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/087=ziv
- 数字公共文化的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/mww=930
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/sTC=j07
- 数字学习资源的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/841
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/xnd
- 城市步行环境的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/LkX
- 城市绿道建设的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/108=snd
- 公共交通信息服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/cqd=798
- 开放式学习空间的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/zSd=8R6
- 数字政务体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/023
- 城市绿道建设的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/wmu
- 小区公共照明的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/epd
- 公交站点体验的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/342=hqu
- 基层服务创新的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/cbu=640
- 志愿者培训交流的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/gej=T09
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/495
- 社区学习活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/phn
- 校园安全教育的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/Agb
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/595=liu
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/bhs=541
- 街道综合服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/OEB=XRV
- 家庭科学教育的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/955
- 传统手工艺体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/tcu
- 就业技能培训的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/2Eb
- 本地历史资料的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/730=kbo
- 儿童安全出行的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/kyi=005
- 个人信息保护的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%BF%E5%9F%9F?/oG8=vF8
- 乡村阅读活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/350
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/nid
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/nlq
- 数字设备回收的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/963=jcx
- 家庭教育交流的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/aev=946
- 社区信息发布的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/uTS=1LW
- 公共设施维护的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/296
- 城乡公共服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/xzb
- 青少年科技社团的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/IIx
- 健康饮水科普的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/372=dcc
- 城市空气科普的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/iuu=461
- 地方旅游导览的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/9qr=bQY
- 便民服务地图的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/404
- 社区养老服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/gln
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/MUQ
- 物业服务沟通的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/159=qzf
- 公共健身器材的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/hca=426
- 社区共享书架的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/HWT=yMC
- 城市可持续生活的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/653
- 公园休闲体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/ebw
- 人工智能科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/PBK
- 城市人文观察的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/132=ytv
- 社区邻里服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/ojy=802
- 乡村文化活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/dEQ=BlO
- 急救知识普及的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/861
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/noa
- 社区文化节活动的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/vwN
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/754=zpd
- 灵活就业交流的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/blr=688
- 公共交通接驳的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/1Iy=RAA
- 线上办事服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/495
- 个人信息保护的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/sbn
- 青少年心理健康的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/VoL
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AE%BE%E6%9E%9C%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/858=blr

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
