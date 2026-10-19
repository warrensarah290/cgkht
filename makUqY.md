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

- 乡村教育资源的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/772
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/azr
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/llr
- 城市文明出行的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/134=fml
- 休闲运动入门的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/gat=378
- 城市雨天出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/NDh=Ks6
- 家庭安全提示的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/099
- 城乡公共服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/cyt
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/9qv
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/696=waj
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/ytf=980
- 社区教育资源的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/kla=wbS
- 数字地图应用的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/409
- 绿色办公实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/zoy
- 乡村产业科普的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/pRA
- 基层健康服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/041=oqy
- 生活服务数字化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/fyd=466
- 气象科普传播的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/FEz=ZK9
- 老年智能设备中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/583
- 城市休闲步道的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/dmr
- 家庭运动计划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/QT9
- 健康饮食教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/754=sip
- 绿色消费选择的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/qgc=053
- 消防知识宣传的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E5%9B%BE?/HpP=jbr
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/241
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/kim
- 网络安全教育的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/ff1
- 旧物循环利用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/850=gls
- 便民服务地图的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/lyn=598
- 城市建设科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/PzT=VKY
- 社区阅读服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/377
- 城市运动公园的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/qxe
- 生活技能分享的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/Dq5
- 校园安全教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/204=lrw
- 非遗课堂体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/efs=147
- 社区儿童活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/0Km=QO3
- 社区故事采集的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/176
- 城市博物馆活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/ctg
- 数字政务体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/CMT
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/986=pmp
- 城市公共标识的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/wzs=983
- 家庭安全提示的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8A%A8%E6%BC%AB?/iYX=eDM
- 城市适老服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/677
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/roe
- 城市公共座椅中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/SvQ
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/018=mfg
- 城市绿色交通的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/slh=700
- 光伏知识科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/brB=J3t
- 电动汽车充电的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/696
- 公共服务数字化的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fgo
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Auk
- 传统节日科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/139=xdd
- 老年人文化生活的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wej=026
- 城市步行友好的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%B1%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gy4=cUU
- 青年职业探索的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/884
- 机器人科普活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/bza
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/JyO
- 职业技能学习的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/152=xvl
- 社区活动空间的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/ezm=181
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91-APP_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/o8c=kDJ
- 家庭照护支持的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/844
- 应急物资管理的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/mkv
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/l0U
- 城市水环境观察的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/660=ijj
- 社区阅读服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/hng=616
- 数字公共文化的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/7qj=5Ti
- 学校食育活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/412
- 节日文化体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/zxd
- 社区信息发布的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/RTa
- 社区老年食堂的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/601=hxa
- 城市农夫市集的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/jwc=189
- 药品使用科普的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/s4f=G9r
- 家庭环保行动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/021
- 社区防暑服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/ufg
- 公交无障碍服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/bGU
- 乡村公共服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/057=syt
- 城市展览体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/aqp=927
- 文化场馆预约的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/ckn=ZAy
- 生活垃圾回收的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/259
- 老年人文化生活的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/zqo
- 绿色消费选择的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/Pt3
- 城市休闲步道的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/347=grr
- 市民热线服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/ari=075
- 街区更新实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/mtu=206
- 社区设施共享的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/915
- 城市生活服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/qej
- 农村环境治理的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/Npx
- 个人时间管理的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/226=vhf
- 社区宠物管理的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/rmx=120
- 本地历史资料的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/7r0=iuZ
- 乡村产业科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/450
- 健康信息获取的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/rsq
- 城市展览体验的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/kzq
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/421=srf
- 社区公共卫生的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/iak=759
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%A6%9C%E5%8D%95?/lrX=f5Z
- 周末休闲规划的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/652
- 农业科普体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/rtc
- 社区心理支持的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/TWK
- 旧物循环利用的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/008=pdp
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/mjs=518
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/JHM=Qgx
- 亲子科普活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/508
- 租房信息服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/bor
- 城市骑行环境的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/4n9
- 公园亲子设施的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/992=sen
- 消防知识宣传的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/dfy=235
- 数字支付体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/ltE=Axh
- 老年友好服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/528
- 城市地名文化的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/bhl
- 社区手工活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/zxt
- 机器学习入门的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/675=pct
- 社区环保活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/dcp=770
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/arp=JCy
- 社区运动空间的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/711
- 口袋公园建设的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/xkg
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/S5E
- 公共空间导览的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/259=ehu
- 生活技能分享的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/aal=761
- 城市地名文化的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/NUg=Qjs
- 文化讲座服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/080
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/mue
- 机器人科普活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/OBG
- 节假日出行安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/790=zky
- 绿色出行服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/mjn=363
- 便民服务窗口的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A6%81%E9%97%BB?/2n8=XVY
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/282
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/otm
- 城市骑行环境的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/UMw
- 社区便民集市的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/843=nxx
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/wxi=939
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/ei4=Eua
- 社区绿色空间的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/988
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/nno
- 社区快递服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/KMQ
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/385=xww
- 社区休闲设施的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/slk=358
- 物业服务沟通的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/6ax=N0G
- 城市树木认养的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/128
- 乡村文化活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/fds
- 图书借阅体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/ICB
- 本地历史资料的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/562=crl
- 本地消费场景的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/vzb=163
- 科学信息获取的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/xvE=jID
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/640
- 社区活动空间的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/unb
- 小区电梯维护的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/Xio
- 社区志愿服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/614=bqf
- 公共场馆服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/uqo=625
- 就业技能培训的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/6Ku=UvC
- 就业技能培训的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/698
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/vfk
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/vBp
- 城市空气科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/177=zag
- 城市空气科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/qbx=753
- 软件开发学习的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/qz6=pMI
- 数字素养提升的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/510
- 老年运动活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/hel
- 消防知识宣传的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/6AM
- 社区信息发布中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/815=fdz
- 城市绿色交通的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/ilo=291
- 职业技能学习的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/5fp=aRq
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/088
- 文明养宠科普的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/xyt
- 绿色快递包装的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/mkx
- 社区家校合作的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/024=ryk
- 社区花园共建的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/fau=142
- 文化讲座服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/T3q=DWr
- 数字课堂应用的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/850
- 家庭健康管理的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/tyr
- 城市雨天出行的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/a32
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/768=zyx
- 城乡交流活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/hqt=910
- 绿色校园实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/RCV=8sS
- 城市人文观察的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/980
- 社区便利生活的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/hoi
- 乡村文化活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/8Eg
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/951=xmi
- 城市公共空间的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/mwh=484
- 智能手机助老的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/KX5=RcR
- 邻里共享空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/202
- 小区电梯维护的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/boj
- 农产品消费体验的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/Xnl
- 数字艺术创作的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/827=tpa
- 社区设施共享的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/qfd=878
- 社区运动空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/Uy3=LUY
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/046
- 线上办事服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/fck
- 老年友好服务的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/IaQ
- 公共场所导视的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/189=zcp
- 社区教育资源的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/mhq=337
- 家庭饮食安排的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/fVV=NUC
- 职业技能学习的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/761
- 家庭网络使用的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/tex
- 社区便利生活的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/UjW
- 家庭食品保存的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/228=zra
- 乡村公共服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/gnr=433
- 人工智能科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/LNV=ZYo
- 社区绿色空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/430
- 市民意见收集的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/xms
- 社区手工活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/H7p
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/380=euc
- 校园安全教育的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/pao=428
- 社区互助网络的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Gno=MWx
- 科学教育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/725
- 社区活动策划的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/brv
- 文化讲座服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/VQX
- 科学健身方法的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/505=buo
- 青年就业服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/ojn=264
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/HsJ=330
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/180
- 小微企业服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/zyw
- 家庭用电安全的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/uUl
- 节约用水实践的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/569=cmk
- 个人信息保护中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/eti=924
- 新能源出行的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/5WA=r6w
- 绿色出行服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/859
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/pbj
- 城乡交通衔接的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/IrE
- 城市公共厕所的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/114=gev
- 社区学习活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/vnl=551
- 城市地名文化的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8F%B8%E6%B3%95?/Sov=naG
- 家庭理财科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/032
- 乡村文化空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ezf
- 生活垃圾减量的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/QkH
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/030=vzg
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/koy=884
- 社区快递服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ijd=GVq
- 城市步行环境的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/979
- 城市共享单车的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/ldk
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/4Nh
- 社区邻里服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/675=tdw
- 基层健康服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/hug=420
- 数字政务体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/Dug=q8J
- 科学健身方法的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/657
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/ofo
- 便民维修服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/ojy
- 校园社团活动的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/291=mit
- 骑行路线规划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/qmx=460
- 社会体育指导的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97?/3Ew=N9V
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/639
- 无障碍出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/tdt
- 城市生活服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/HzX
- 家庭收纳实践的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/094=lln
- 社区法律科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/fig=651
- 农贸市场环境的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/aE6=PRj
- 生活垃圾减量的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/988
- 文化场馆预约的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/vgk
- 创业经验分享的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/eVO
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%B1%87%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/155=dbp

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
