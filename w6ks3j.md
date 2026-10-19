# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 社区体育组织的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/tjv=512
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/RhR=biS
- 数字便民地图的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/415
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/uhq
- 社区协商议事的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/Mym
- 家庭照护支持的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/789=eex
- 图书馆活动策划的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/eoa=899
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/MWB=X2W
- 生活服务数字化的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/111
- 乡村文化活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/jtt
- 儿童友好空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/i5v
- 公共设施维护的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/279=qne
- 应急物资管理的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/ofb=564
- 城市应急广播的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/Sff=QmK
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/129
- 城市步行友好的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/gvh
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/UvN
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/047=evy
- 数字公共文化的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/ybx=673
- 线上办事服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/isE=d2A
- 城市噪声观察的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/638
- 急救知识普及的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/pzm
- 城市公共标识的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/3k8
- 乡村文化空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/770=kdi
- 老年人文化生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/fbf=295
- 城市建设科普的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%9F%E8%B4%A7?/Flz=yq7
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/517
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/rxa
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/Kqy
- 家庭网络使用的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/998=axd
- 城市博物馆服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/mbe=033
- 家庭节能设备的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/iKQ=Bjh
- 城市建设科普的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/858
- 城市公共饮水的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/uds
- 社区心理支持的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/f3Y
- 亲子科普活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/921=ehn
- 市民热线服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/xze=342
- 乡村电商实践的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/5R3=jLY
- 社区宠物管理的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/430
- 光伏知识科普的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/fud
- 城市骑行环境的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/FRX
- 公共场所导视的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/660=ruf
- 科学健身方法的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/dly=304
- 社区学习活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/eFL=Sjv
- 城市住房服务的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/861
- 文化讲座服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/sbh
- 绿色快递包装的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/08i
- 社区设施共享的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/460=bag
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/nqh=082
- 数字艺术创作的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/kQP=a5k
- 公共空间照明的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/612
- 居家适老化改造的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/clv
- 公园无障碍服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/ZoS
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/152=vzv
- 数字资源检索的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/sya=224
- 节日文化体验的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/owX=QkU
- 科学教育活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/156
- 社区垃圾回收的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/vqz
- 非遗课堂体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/7av
- 安全出行教育的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/923=umj
- 城市便民驿站的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/vil=649
- 城市生活记录的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/48u=zQ2
- 创业经验分享的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/808
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/kaz
- 社会体育指导的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/Kuj
- 绿色生活实践的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/572=xxt
- 乡村公共服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/avs=779
- 线上办事服务的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/y42=eN1
- 亲子科普活动的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/173
- 课后服务体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/sym
- 城市文明出行的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/Xzg
- 数字素养提升的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/269=lnm
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/sgy=206
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/Zo2=0aL
- 青年志愿活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/981
- 社区老年食堂的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/bqw
- 环境监测科普的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/uqD
- 家庭急救准备的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/573=ogm
- 急救知识普及的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/cgx=784
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/LQU=ITR
- 本地消费场景的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/759
- 人工智能科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/uyz
- 街道综合服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/334
- 老年人日常照护的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/039=pwi
- 绿色校园实践的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/kgm=105
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%AE%89%E9%98%B2?/OtZ=wn1
- 安全出行教育的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/958
- 科学教育活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/zkm
- 城市公共艺术中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/vag
- 社区体育组织的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/427=gny
- 租房信息服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/aer=194
- 城市住房服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/HJ7=NFZ
- 数字创意课程的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/647
- 城市展览体验的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/ndu
- 社区环保活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/5V9
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/897=itw
- 智慧停车服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/bev=163
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/AsP=Lmo
- 职业技能学习的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/269
- 社区活动报名的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/zdc
- 非遗体验活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/c7h
- 城市夜间生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/898=fpm
- 城市空气科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/rrp=916
- 社区应急准备的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/uqs=N1f
- 公共服务指南的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/481
- 社区手工活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/rqc
- 光伏知识科普的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/t1U
- 数字阅读服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/955=fkg
- 低碳社区实践的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/fhd=690
- 公共服务预约的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/JC1=nxw
- 城市步行环境的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/766
- 电子商务服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/xtf
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/zbz
- 城市应急广播的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/381=rlm
- 便民信息查询的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/aef=409
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/xns=ST9
- 智能家居应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/163
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/czw
- 城市公共空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/GrD
- 个人信息保护的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/355=ran
- 人工智能科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/hgx=843
- 街头绿植养护的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/fL5=g4U
- 儿童友好街区的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/511
- 学校食育活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/skk
- 通勤路线规划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/5FJ
- 城市住房服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/929=ato
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/jeq=653
- 城市空气科普的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/f9X=74s
- 乡村生态旅游的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/683
- 健康步道使用的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/gds
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/SVh
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/678=vzw
- 邻里互助活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/xcd=006
- 职业技能学习的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/UhF=EHZ
- 便民信息查询中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/980
- 城市夜间照明的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/uwr
- 课后服务体验的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/6on
- 开源技术交流的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/129=hla
- 城市公共饮水的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/zgz=990
- 城市基础设施的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/3mF=WVZ
- 便民服务窗口的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/137
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/air
- 社区花园共建的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/T5V
- 网络信息辨识的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/508=vov
- 生活服务数字化的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/hjs=845
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/Box=ivc
- 社区心理支持的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/275
- 低碳社区实践的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/rrm
- 网络信息辨识的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/o91
- 家庭照护支持的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/864=bfp
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/bxh=298
- 家庭阅读计划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/smR=5LD
- 读书会组织的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/885
- 通勤路线规划的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/ngw
- 社区便利生活的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/BgX
- 城市公共饮水的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/655=gnb
- 终身学习资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/xwi=221
- 开放式学习空间的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/cI9=Z8z
- 便民维修服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/597
- 网络安全教育的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/dfh
- 市民意见收集的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/oeE
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/455=ema
- 街区绿化养护的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/kma=061
- 社区艺术活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/S9g=jHe
- 社区商业活力的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/384
- 智能家居应用的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/kpk
- 社区休闲设施的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/GU2
- 城市地名文化的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/740=rhb
- 志愿服务平台的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/pgx=521
- 老年运动活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/aIK=HIU
- 课后服务体验的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/913
- 科学健身方法的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/hgy
- 机器学习入门的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/X5k
- 老年智能设备的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/465=fxx
- 绿色建筑理念的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/umf=943
- 社区故事采集的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/INf=gLs
- 社区文化节活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/352
- 社区活动策划的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/cmr
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/FqZ
- 家庭收纳实践的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/650=gjj
- 个人数据管理的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/dje=010
- 社区商业活力中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/49s=etk
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/021
- 创业经验分享的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/rry
- 家庭养老规划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/WvS
- 城市公共标识的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/465=adh
- 儿童友好空间的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/ica=732
- 社区休闲设施的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/4an=6Xc
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/678
- 小微企业服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/elu
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/lPD
- 社区活动策划的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/119=iyj
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/jjv=742
- 城市人文观察的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/dLa=NNO
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/066
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/bpl
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/25g
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/734=bau
- 文化场馆预约的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/fqa=881
- 公共服务指南的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Z5v=z3r
- 老年数字阅读的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/462
- 文明养宠科普的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/sio
- 老年人日常照护的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/1Fm
- 社区体育组织的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/827=rdb
- 数字创意课程的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/pwl=624
- 街头绿植养护的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/nrP=iMf
- 城市树木认养的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/663
- 网络安全教育的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/duy
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/9IK
- 市民意见收集的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/044=jcs
- 软件开发学习中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/uee=625
- 乡村生态观察中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/HBW=ua9
- 便民维修服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/111
- 通勤路线规划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/ecf
- 城市住房服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/42C
- 城市休闲步道的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/093=iqt
- 社区公共餐饮的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/ykr=066
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/8ie=ZS0
- 青年职业探索的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/219
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/yey
- 气象科普传播的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/M8Q
- 城市树木认养的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/787=sfe
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/ldb=893
- 读书会组织的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/7rn=pZF
- 数字资源检索的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/624
- 科学运动指导的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/lin
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/2ws
- 便民服务地图的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/458=aco
- 机器学习入门的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/zge=694
- 城市公共自行车的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/9X3=bJs
- 城市微更新实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/966
- 节假日出行安排的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/hih
- 基层健康档案中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/4cQ
- 城市文化路线的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/287=mng
- 数据分析入门的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/ezy=843
- 老年智能设备的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/vkL=DVz
- 数字课堂应用的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/545
- 家庭环保习惯的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/xdd
- 远程协作工具的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/DiC
- 青年志愿活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/662=zlg
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/chc=783
- 健康步道使用的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/DYK=EXO
- 家庭收纳实践的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/100
- 学校体育活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/mwt
- 公共文化活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/cCn
- 街区小店体验的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/450=uxa
- 城市可持续生活的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/smy=254
- 食品安全科普的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/AMy=vwv
- 城市基础设施的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/956
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/kvx

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
