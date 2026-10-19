# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 家庭收纳实践的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/962
- 电动汽车充电的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/ddo
- 社区儿童活动的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/K2A
- 数字艺术创作的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/631=eha
- 城市地名文化的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/jdt=362
- 机器人科普活动的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/5o0=cOK
- 校园节能行动的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/677
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/hxb
- 城市人文观察的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/mA4
- 节日文化体验的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/128=bzi
- 公共服务指南的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/gon=107
- 数字课堂应用的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/eba=Hq7
- 消防知识宣传的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/667
- 网络信息辨识的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/oqd
- 环境教育课程的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/4sQ
- 社区志愿服务的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/844=zre
- 城市文化路线的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/ymq=277
- 软件开发学习的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/Wiz=Tg5
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/881
- 科学观察活动的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/cqo
- 公共场所导视的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/C23
- 本地消费场景的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/912=dwi
- 居家防滑改造的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/msp=109
- 健康饮食教育的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/Grr=8r4
- 城市可持续生活的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/560
- 乡村文化活动的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/gyp
- 乡村阅读活动的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/doU
- 数字档案服务的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/291=gjd
- 软件开发学习的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/kti=498
- 数字创意课程的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/8KX=cpF
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/954
- 社区运动空间的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/jck
- 绿色出行服务的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/EWO
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/857=mui
- 城市公共空间的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/qsu=242
- 图书借阅体验的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/9hv=NTs
- 社区养老服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/258
- 职业技能学习的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/fxd
- 校园阅读活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/txn
- 个人数据管理的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/504=sce
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/eea=071
- 社区知识分享的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/Mjn=CXU
- 公共服务评价的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/029
- 社区科普课堂中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/wpi
- 城市农夫市集的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/YIm
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/824=fru
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/rlh=284
- 社区休闲设施的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/klN=fw4
- 城市地名文化的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/767
- 街区道路维护的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/uca
- 开放数据应用的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/FKV
- 生活服务数字化的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/594=irj
- 社区交通安全的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/fwm=581
- 城市水环境观察的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/Kcc=Nfs
- 邻里互助活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/170
- 乡村公共阅读的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/jhk
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/hyQ
- 社区儿童活动的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/178=lsb
- 节能家电使用的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/bpj=410
- 青年职业探索的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E4%BC%98%E9%85%B7%E6%95%B0%E8%AF%BB?/3ug=GPe
- 农产品消费体验的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/918
- 街区道路维护的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/zgx
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/GWO
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/123=ykp
- 乡村文化空间的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/waj=504
- 社区便民集市的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/JwF=GyZ
- 学校食育活动的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/907
- 数字政务体验的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/abi
- 社区家政服务的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/hml
- 智慧停车服务的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/735=jkx
- 课后服务体验的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/wgi=968
- 光伏知识科普的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/n0C=pie
- 校园社团活动的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/816
- 智慧停车服务的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/sad
- 家庭网络使用的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/P32
- 社区活动策划的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/434=usl
- 数字便民地图的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/gbn=303
- 居民健康教育的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/9Kc=qqv
- 公共空间照明的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/152
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/gcv
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/5kL
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/571=wao
- 城市基础设施的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/sut=725
- 本地旅行体验的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/SNS=e3W
- 老年人日常照护的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/836
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/qlj
- 社区花园共建的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/dfU
- 学校食育活动的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/363=ntm
- 节日文化体验的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/qku=468
- 开放式学习空间的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/wT6=waj
- 智慧停车服务的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/169
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/nnh
- 职业技能学习的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/uaT
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/073=whn
- 街道综合服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/eps=978
- 物业服务沟通的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/TJq=e8X
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/371
- 无障碍出行的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/eqe
- 在线学习体验的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/icZ
- 节气饮食文化的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/919=vog
- 社区托育服务的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/ttv=869
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%913%E5%88%86_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/qH2=LEY
- 急救知识普及的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/187
- 社区故事采集的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/pqc
- 健康步道使用的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/DZx
- 市民热线服务的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/686=tpw
- 科学运动指导的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/hib=040
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_360%E5%8E%86%E5%8F%B2?/Zjv=yUo
- 在线教育体验的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/272
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/dnq
- 绿色校园实践的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/XbI
- 智能家居应用的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/243=qjp
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/gta=256
- 软件开发学习的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/h8g=qwS
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/846
- 小区电梯维护的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/yku
- 节日文化体验的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/6yl
- 公园休闲体验的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/406=rqm
- 生成式工具使用的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/hry=113
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/Gqb=Ygj
- 社区家校合作中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/707
- 信息无障碍体验的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/mch
- 数字便民地图的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/tNk
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/948=nzq
- 环境教育课程的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/xpz=119
- 城市步行友好的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/3qp=SsP
- 读书会组织的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/680
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/xfa
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/bI2
- 城市夜间照明的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/311=jhk
- 社区停车服务的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/xyj=757
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/CVO=dqo
- 家庭食品保存的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/224
- 乡村公共阅读的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/cxy
- 在线教育体验的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/7Tb
- 城市应急科普的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/593=oag
- 亲子阅读活动的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/tsv=082
- 家庭网络使用的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%911.98_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/r2G=mcO
- 城市文化路线的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/630
- 公共设施维护的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/xxu
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/kYk
- 新能源知识普及的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/933=wjz
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/apn=127
- 街区更新实践的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E8%82%A1?/DB4=6RK
- 新能源出行的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/556
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/jtr
- 公共健身器材的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/o2D
- 社区家政服务的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/774=oeo
- 青年职业探索的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/itg=035
- 线上办事服务的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%B0%E9%97%BB?/tna=rG9
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/244
- 城市休闲步道的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/fle
- 社区修缮行动的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/tF0
- 图书馆活动策划的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/052=rkq
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/mce=987
- 社区消防演练的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/3Kq=CI0
- 健康饮水科普的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/560
- 城市公共饮水中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/ooy
- 社区交通安全的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/IWW
- 城市噪声观察的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/622=unf
- 地方美食文化的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/nxs=620
- 社区文化传播的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/3uv=x0p
- 城市文明实践的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/379
- 节日文化体验的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/ker
- 节约用水实践的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/KQR
- 城乡交流活动的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/473=gre
- 城市建设科普的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/rjm=630
- 家庭食品保存的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/bEl=YsD
- 社区活动策划的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/880
- 食品安全科普的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/yzj
- 消防知识宣传的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/9Md
- 公共设施使用的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/829=vmz
- 乡村公共服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/pet=501
- 儿童户外活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/ixp=anW
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/204
- 家庭收纳实践的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/hym
- 社区绿色空间的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/VUX
- 城市休闲步道的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/184=amn
- 城乡公共服务的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/iwp=600
- 社区法律科普的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%B4%A2%E6%8A%A5?/P4g=Vj4
- 家庭志愿活动的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/121
- 数字政务体验的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/ozl
- 家庭健康管理的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/Jwe
- 软件开发学习的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/199=soy
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/bvi=545
- 社区停车服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/juH=MDV
- 休闲运动入门的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/801
- 绿色生活实践的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/zzk
- 邻里共享空间的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/cmV
- 公共空间安全的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/752=yxy
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/ker=984
- 地方美食文化中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/WVm=Q15
- 软件开发学习的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/201
- 课后服务体验的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/mcr
- 社区运动空间的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/8Tv
- 老年学习活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/646=rzx
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/isu=068
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/54s=xwC
- 数字政务体验的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/149
- 城市水环境观察的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/zzq
- 公交无障碍服务的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/K2s
- 儿童友好街区的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/519=rlq
- 街头绿植养护的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/vct=088
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/RgK=aen
- 社区便民集市的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/408
- 城市绿道建设的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/aza
- 科学健身方法的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/jnp
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/122=ftx
- 青年职业探索的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/qrv=710
- 地方文化传播的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86pk10%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/xcN=pX7
- 社区商业活力的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/164
- 城市共享单车的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/bjl
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/JsC
- 家庭阅读计划的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/072=aln
- 城市展览体验的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/dhk=692
- 开源技术交流的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BD%A9%E5%AF%BC%E5%B8%88qq_%E6%96%B0%E6%B5%AA%E6%88%BF%E4%BA%A7?/Ti6=Zbf
- 线上阅读资源的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/919
- 非遗课堂体验的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/upa
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/p7V
- 数字档案服务的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/093=uqr
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/klo=218
- 乡村公共阅读的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E7%A8%B3%E6%89%93%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/yNA=Qw1
- 公共空间导览中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/038
- 城市基础设施的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/iwt
- 公共健身器材的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/VWv
- 基层健康档案的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/838=qqr
- 城市公共空间的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/dks=893
- 城乡交流活动的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%85%B3%E4%BA%8E%E5%88%86%E5%88%86%E5%BD%A9%E6%89%93%E6%B3%95_%E4%BA%9A%E5%A4%AA%E8%B4%A2%E7%BB%8F?/mTh=ndx
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/587
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/wud
- 社区便民集市的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/Xcq
- 智慧停车服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/653=pmf
- 城市游园体验的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/zcm=860
- 城市公共标识的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/Gnv=wN7
- 健康信息获取的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/466
- 劳动教育实践的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/jnh
- 社区养老服务的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/EG4
- 社区教育资源的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/222=yck
- 儿童户外活动的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/fba=998
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BD%A9%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%AE%89%E9%98%B2?/itP=NAd
- 新能源出行的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/867
- 家庭网络使用的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/fvx
- 机器学习入门的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/D71
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/251=xbe
- 网络安全教育的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/acx=192
- 电动汽车充电的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B6%B3%E5%BD%A923098%E6%9C%9F%E6%8E%A8_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/jsl=vxj
- 公共场所导视的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_23098%E6%9C%9F%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/831
- 老年友好服务的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_23098%E6%9C%9F%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/irq
- 绿色生活实践的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_23098%E6%9C%9F%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/zqH
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_23098%E6%9C%9F%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/609=vwg

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
