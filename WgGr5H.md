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

- 家庭运动计划的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/xqa=909
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/aaE=dIs
- 社会体育指导的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/252
- 社区教育资源的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/yur
- 家庭节能实践的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/7bD
- 终身学习资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/029=oue
- 家庭运动计划的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ngw=060
- 小微企业服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/mQq=f6L
- 社区便民集市的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/131
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/fwf
- 网络安全教育的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/JGe
- 老年人文化生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/623=hhb
- 基层服务创新的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/cmd=887
- 老旧小区改造的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%81%A5%E5%BA%B7?/V86=MW9
- 城市社区治理的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/428
- 家庭网络使用的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/oxf
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/QJr
- 老年学习活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/151=iwo
- 节能生活方式的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/isd=189
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/8sr=p7m
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/306
- 乡村公共阅读的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/itg
- 社区文化节活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/wX3
- 邻里互助活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/316=dns
- 职业技能学习的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/oqi=207
- 社区养老服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/OdV=qWM
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/503
- 城市可持续生活的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/uxj
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/1bQ
- 青少年科普实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/710=jjr
- 城市基础设施的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/bnh=330
- 家庭照护支持的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/cI6=nSb
- 家庭健康管理的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/930
- 校园安全教育的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/unz
- 创业经验分享的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/vLT
- 城市人文观察的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/004=qmb
- 社区应急准备的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/bzd=465
- 城市农夫市集的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/Xix=if9
- 公共设施使用的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/193
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/usy
- 城市住房服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/olH
- 城市应急广播的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/031=iol
- 城市绿道建设的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/uaz=421
- 数字创作工具的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/c6J=ZiD
- 绿色办公实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/398
- 新能源出行的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/nws
- 城市应急科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/sqT
- 青少年户外教育的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/749=mqs
- 数字公共文化的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/bjc=616
- 数字艺术创作的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/86K=u0N
- 乡村公共文化的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/906
- 街区更新实践的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/otc
- 便民服务窗口的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/06R
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/867=vda
- 绿色生活实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/ceg=808
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/niL=x4Q
- 社区体育组织的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/399
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/stj
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/0qX
- 低碳社区实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/504=vsi
- 城市骑行环境的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/hfi=179
- 农业科普体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/3WS=Fva
- 网络安全教育的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/544
- 药品使用科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/mwe
- 城市绿道建设的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/7lv
- 公共空间照明的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/608=rhg
- 城市体育设施的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/adk=840
- 志愿者培训交流的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/wuQ=h4R
- 数字档案服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/328
- 家庭园艺实践的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/qzo
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/ooK
- 城市噪声观察的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/270=upz
- 社区防暑服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/hgc=422
- 健康信息获取的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/W09=Cxd
- 老年友好服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/578
- 青少年心理健康的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/mjc
- 数字资源检索的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/Pkn
- 个人信息保护的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/351=goi
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/zen=901
- 节能生活方式的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/8ju=OAX
- 生活垃圾减量的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/587
- 老年人文化生活的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/ukl
- 城市人文观察的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/8ZO
- 社区商业活力的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/013=mdm
- 社区养老服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/cfl=503
- 城市运动公园的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%AE%BF%E8%B0%88?/SVo=Xr5
- 街头绿植养护的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/992
- 城市空气科普的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/ztu
- 在线教育体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/PSE
- 旧物循环利用的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/355=fgd
- 数字公共文化的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/pyk=658
- 读书会组织的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/AIc=oB5
- 便民维修服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/708
- 社区交通安全的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/kua
- 科技馆参观体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/B4n
- 学校食育活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/612=vhr
- 劳动教育实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/sob=877
- 健康饮水科普的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/eVB=0Y0
- 文化讲座服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/166
- 社区阅读服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/mse
- 家庭养老规划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/wwt
- 休闲运动入门的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/798=whg
- 城市文明出行的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/usl=053
- 环境教育课程的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%94%BF%E7%AD%96?/7lm=N3s
- 城市博物馆服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/096
- 校园节能行动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/csq
- 跨代沟通活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/F9P
- 社区故事采集的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/275=ota
- 医院导诊服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/scj=749
- 社区家校合作的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/ebF=gbp
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/344
- 健康步道使用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/fjp
- 数字便民地图的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/dKM
- 社区生活指南的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/944=uyq
- 地方戏曲体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/bqh=275
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/byO=NGI
- 城市文化路线的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/611
- 人工智能科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/kqb
- 公园休闲体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/pLE
- 乡村教育资源的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/226=hzy
- 乡村文化空间的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/zjr=996
- 安全出行教育的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/0Ot=BFp
- 小区电梯维护的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/779
- 家庭饮食安排的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/oxm
- 街区绿化养护的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/oSq
- 城市雨天出行的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/989=uua
- 城市展览体验的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/why=462
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/0Ab=m6T
- 社区家校合作的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/516
- 老年人文化生活中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/kil
- 图书馆数字服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/dLf
- 城市慢行系统的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/818=bqb
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/eec=798
- 数字便民地图的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/VUR=W9k
- 校园社团活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/242
- 信息无障碍体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/obw
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/v1W
- 家庭环保行动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/867=vtq
- 城市文化路线的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/lvj=282
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/IsE=Zps
- 城乡公共服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/940
- 信息无障碍体验的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/cdi
- 公共服务评价的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/wxp
- 通勤路线规划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/768=pwi
- 城市建设科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/mfl=050
- 数字创作工具的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/XSD=7pw
- 无障碍出行的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/107
- 城市休闲步道的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/kdo
- 乡村文化空间的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/EBR
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/178=msn
- 全民健身活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/eyk=513
- 就业技能培训的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/3te=SNT
- 街头绿植养护的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/206
- 城乡公共服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/uee
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/T7M
- 公共空间安全中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/420=rni
- 家庭科学教育的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/tyn=415
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/x5G=Mxi
- 青少年户外教育的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/631
- 社区儿童活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/jqs
- 数字素养提升的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/izG
- 邻里互助活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/965=sco
- 日常摄影记录的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/mvd=906
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/Hv6=WHo
- 绿色办公实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/930
- 休闲运动入门的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/pka
- 社区停车服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/68x
- 社区花园共建的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/915=mhn
- 环境教育课程的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/cdy=237
- 通勤路线规划的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/N6c=5RN
- 校园社团活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/326
- 社区科普课堂的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/zkn
- 城市便民驿站的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/sLs
- 乡村公共阅读的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/859=rdr
- 小区电梯维护的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/pnd=283
- 乡村教育资源的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%B8%E6%98%93%E8%B4%A2%E7%BB%8F?/h5M=G6s
- 公共卫生设施的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/656
- 公交站点体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/tvm
- 科学信息获取的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/9AF
- 家庭安全提示的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/856=scg
- 校园安全教育的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/boa=698
- 小区公共照明的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/Elw=1Zb
- 传统节日科普的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/271
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/fvt
- 家庭收纳实践的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/jHN
- 家庭科学教育的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/942=dzb
- 社区休闲设施的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/qpf=209
- 智慧城市体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/z8O=emc
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/105
- 公共空间安全的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/avp
- 社区学习活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/zOH
- 科学运动指导的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/454=ada
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/dcf=155
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/X1n=KN1
- 家庭网络使用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/023
- 开放数据应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/qdc
- 城市应急广播的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/djw
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/996=eed
- 小区停车协商的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/sxb=149
- 城市博物馆服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%95%85%E6%B8%B8?/iiw=afE
- 劳动教育实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/553
- 公共设施使用的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/gsj
- 智能手机助老的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/BZD
- 乡村生活观察的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/973=kpa
- 公交无障碍服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/kxg=705
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/8vS=6ry
- 青年就业服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/393
- 公共交通信息服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/jgi
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/zfR
- 社区知识分享的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/512=ddj
- 家庭用电安全的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/pke=307
- 家庭养老规划的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/Ied=d4l
- 社区故事采集的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/306
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/qth
- 乡村公共服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/TyX
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/391=pcn
- 地方美食文化中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/ueq=301
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/4Xz=D0F
- 青年志愿活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/237
- 人工智能科普的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/ljf
- 线上阅读资源的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/Y0l
- 个人数据管理的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/871=tai
- 节能家电使用的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/taq=695
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E4%BF%A1%E8%B4%B7?/Dvc=jWS
- 公共设施维护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/604
- 家庭消费规划的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/tir
- 通勤路线规划的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/Sh4
- 公共服务指南的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/732=rrn
- 城市公共标识的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/sck=031
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/if8=Q3Y
- 社区老年食堂的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/296
- 儿童友好空间的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/vnj
- 城市展览体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/Lad
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/500=ujg
- 图书馆活动策划的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/mwm=570
- 社区公共卫生的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/2aJ=UkW
- 职业技能学习的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/389
- 便民服务地图的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/xby
- 生活技能分享的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/M6x
- 街头绿植养护的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/493=laq
- 本地历史资料的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/vad=146
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E8%AF%84%E8%AE%BA?/dQy=SNg
- 光伏知识科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/314
- 家庭园艺实践的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/alr
- 公共空间导览的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/A3A
- 小区公共照明的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/741=cmc
- 街区更新实践的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/reh=885
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/PNi=ENk
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/261
- 城乡公共服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/atb

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
