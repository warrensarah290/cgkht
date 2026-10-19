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

- 文化讲座服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/bhw=083
- 网络安全教育的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/eKQ=Vnx
- 读书会组织的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/731
- 社区停车服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/nmo
- 节约用水实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/aMy
- 社区故事采集的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/593=lsr
- 城市应急科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/ywp=551
- 亲子阅读活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/vsn=4Vm
- 公共服务咨询的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/909
- 乡村公共文化的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/hfh
- 社区协商议事的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/EDN
- 绿色生活实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/091=eow
- 农贸市场环境的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/ilq=269
- 生活技能分享的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/spP=4md
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/952
- 生活技能分享的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/mng
- 城市运动公园的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/DzW
- 终身学习资源的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/482=ajv
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/xka=108
- 社区艺术活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/LMn=g1C
- 便民维修服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/392
- 城市水环境观察的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/btl
- 社区运动空间的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/vL5
- 城市公共厕所的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/391=fuf
- 校园安全教育的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/qmy=631
- 城市基础设施的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/D9q=z2u
- 全民阅读推广的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/051
- 城市应急科普的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/zkg
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/CqV
- 居家适老化改造的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/418=jox
- 旧物循环利用的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ktr=146
- 公共图书馆服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/uCZ=0Gx
- 社区修缮行动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/575
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/kvp
- 安全出行教育的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/3nn
- 家庭教育交流的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/361=mwo
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/hnv=750
- 公共服务评价的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/4mE=gCe
- 终身学习资源的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/860
- 城市步行环境中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/dqc
- 社区科普课堂的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/bdz
- 城乡公共服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/555=izs
- 课后服务体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/uba=121
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%81%92%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/iU5=3qq
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/334
- 公共服务指南的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/ldb
- 日常摄影记录的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/YK9
- 城市人文观察的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/293=kbr
- 基层医疗预约的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/rzd=461
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/6Dh=Pj2
- 城乡交流活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/911
- 在线教育体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fdn
- 小区电梯维护的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/PiB
- 亲子科普活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/774=oco
- 居家适老化改造的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eyy=116
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%81%92%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/4Jv=9co
- 数据分析入门的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/497
- 医院导诊服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/ycw
- 家庭教育交流的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/6vo
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/054=rbi
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/ydl=896
- 在线教育体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Ehh=9fT
- 公共设施维护的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/771
- 家庭健康科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/wcl
- 口袋公园建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/Ib6
- 社区养老服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/906=xih
- 家庭饮食安排的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/cel=351
- 数字创意课程的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/0zf=NfU
- 城市可持续生活的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/470
- 休闲运动入门的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/vuv
- 农村环境治理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/yxS
- 社区艺术活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/458=gny
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/jls=070
- 城市夜间照明的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91-%E6%B3%A8%E5%86%8C_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/Kb2=CyS
- 生活技能分享的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/544
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/veu
- 社区健康讲座的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/Nuz
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/894=aki
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/cgd=106
- 社区儿童活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/5r2=nhK
- 绿色生活实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/131
- 家庭急救准备的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/qok
- 地方文化传播的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/JWo
- 城市公共空间的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/987=obm
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/lyb=834
- 社区信息发布的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%81%92%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%BC%E8%89%BA?/Dbe=A00
- 食品安全科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/331
- 线上阅读资源的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/jjo
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/TCR
- 绿色办公实践的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/765=lqq
- 机器人科普活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/rfs=016
- 消防知识宣传的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%81%92%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/rJ6=Vs6
- 生成式工具使用的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/111
- 电子商务服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/cus
- 公共交通接驳的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/wIW
- 急救知识普及的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/514=gzt
- 绿色消费选择的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/foi=441
- 城市文明出行的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%AF%8D%E5%A9%B4?/DF3=9Ql
- 家庭环保行动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/335
- 健康信息获取的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/vcv
- 居民健康教育的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/qFD
- 社区停车服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/799=jgm
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/beq=834
- 城市文化路线的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/ZuU=lC7
- 数字素养提升的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/838
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/rsp
- 家庭节能实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/lGe
- 社区心理支持的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/197=wch
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/xsc=940
- 生活服务数字化的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/5Fr=TjT
- 数字地图应用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/513
- 城市绿道建设中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/cor
- 城市地名文化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/zc7
- 数字支付体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/022=pgz
- 科普展览体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/vte=812
- 应急物资管理的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/KGF=cWG
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/812
- 传统手工艺体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/sqo
- 乡村生态观察的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/hBS
- 城市应急科普的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/752=lbr
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/ktx=548
- 家庭食品保存的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/N9K=kWy
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/776
- 儿童运动体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/cob
- 数字课堂应用的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/MI8
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/010=psv
- 农产品消费体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/qhr=137
- 小区停车协商的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/g6p=d3R
- 公共服务评价的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/272
- 无障碍信息设计的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/jcg
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/fVh
- 就业技能培训的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/648=zex
- 无障碍信息设计的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/zsy=457
- 公交无障碍服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/Erp=RMs
- 数字创作工具的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/331
- 光伏知识科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/mnl
- 灵活就业交流的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/zBr
- 城市慢行系统的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/828=ofk
- 数字设备回收的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/jjs=229
- 乡村教育资源的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/c8Z=9TX
- 便民信息查询的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/927
- 运动安全知识中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/rjp
- 学校食育活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/ggg
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/039=yge
- 城市步行友好的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/tmk=308
- 公共设施使用的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/MrI=krH
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/393
- 社区快递服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/uwr
- 社区生活指南的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/r5t
- 光伏知识科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/942=msg
- 家庭志愿活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/fef=062
- 健康步道使用的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/kBQ=Kpj
- 社区共享书架的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/402
- 社区老年食堂的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/lcm
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/BEG
- 社区便利生活的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/117=mnh
- 社区快递服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/dpv=013
- 乡村电商实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/ufk=rYb
- 社区停车服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/031
- 科技馆参观体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/yjz
- 乡村生态观察的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/K3c
- 社区公共卫生的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/644=hli
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/hey=448
- 地方旅游导览的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/O6n=oTw
- 城市住房服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/326
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/dtm
- 乡村电商实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/2ar
- 社区绿色空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/732=bvt
- 公共交通接驳的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/jpo=668
- 公共健身器材的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/uqC=hFH
- 老年学习活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/372
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/jpg
- 市民意见收集的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/ZWz
- 儿童安全出行的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/257=fgb
- 急救知识普及的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/rqa=169
- 本地旅行体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/X8r=8IH
- 劳动教育实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/208
- 青少年心理健康的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/yph
- 社区慢性病防控的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/hxB
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/362=lsz
- 公共空间照明的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/rdh=577
- 节能生活方式的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/Yit=vB5
- 线上阅读资源的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/699
- 公园亲子设施的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/kus
- 地方文化传播的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/sUj
- 新能源出行的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/512=tvg
- 乡村文化活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/rcx=215
- 基层健康服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/05W=PKW
- 城市微更新实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/370
- 城市公共自行车的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/sbv
- 家庭科学教育的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/X87
- 线上阅读资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/854=vhd
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/jut=275
- 健康饮食教育中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/39A=PXy
- 机器学习入门的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/212
- 公园亲子设施的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/qri
- 城市公共厕所的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/85D
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/117=nhn
- 公共空间休憩的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/upx=055
- 城市夜间生活中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/Vzj=kLD
- 绿色出行服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/678
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/cwl
- 节气饮食文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/9Gx
- 绿色建筑理念的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/244=auq
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/euo=140
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/dxc=eMA
- 街区更新实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/889
- 城市社区治理的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/hfm
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/rRw
- 科学信息获取的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/724=lei
- 生成式工具使用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/dbi=574
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/m2H=Z8C
- 开放数据应用的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/364
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/guv
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/aAw
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/005=ytq
- 数字资源检索的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/def=565
- 家庭网络使用的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/aaC=WRb
- 青少年编程学习的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/115
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/vsg
- 绿色出行服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/LSv
- 社区学习活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/645=hhe
- 家庭健康管理的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/zes=328
- 便民服务地图的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/SIo=3Xv
- 家庭环保习惯的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/512
- 家庭理财科普的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/sfm
- 绿色生活实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/j4g
- 户外活动组织的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/241=vpy
- 城市水环境观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/vzo=121
- 家庭消费规划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/dG7=UMZ
- 城市共享单车的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/238
- 公交站点体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/owi
- 家庭饮食安排的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/6jB
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/485=wli
- 公园休闲体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/fvp=064
- 社区托育服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/6ma=j3K
- 社区知识分享的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/437
- 软件开发学习中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/msq
- 应急物资管理的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/RSh
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/234=scw
- 地方戏曲体验的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/mbk=316
- 课后服务体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/aGq=8ri
- 公共设施维护的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/880
- 城市体育设施的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/wdu
- 家庭安全提示的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/x7x
- 城市步行环境的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/520=kfh
- 数字地图应用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/xed=968
- 信息无障碍体验的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/Mnt=75s
- 数字档案服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/023
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/wtm

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
