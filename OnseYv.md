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

- 城市生活服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/718
- 社区公共卫生的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/anv
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/Uvd
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/412=yce
- 开源技术交流的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/avc=698
- 城乡公共服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/mlp=pcL
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/405
- 公交站点体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/kov
- 家庭照护支持的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/0aO
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/973=eoz
- 城市公共标识的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/cgc=507
- 节约用水实践的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/fQg=XyZ
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/173
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/igs
- 社区公共卫生的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/IX2
- 社区庭院绿化的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/096=zrg
- 绿色出行服务的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/cxn=595
- 城市共享单车的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/X1n=RWS
- 电子商务服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/820
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/cuz
- 校园阅读活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/lW0
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/423=qqg
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/imp=038
- 地方美食文化的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/7zZ=6Jc
- 日常摄影记录的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/139
- 运动安全知识的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/ixk
- 城市建设科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/Eoq
- 社区环保活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/443=pso
- 公益活动组织的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/ycq=675
- 职业技能学习的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%BF%AB%E6%8A%A5?/H5c=Rpp
- 社区学习活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/290
- 家庭网络使用的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/oqh
- 社区花园共建的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/Aqg
- 青年职业探索的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/258=sml
- 节约用水实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/etr=190
- 城市公共厕所的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/XfO=AzQ
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/278
- 社区心理支持的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/wcw
- 社区知识分享的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/PcK
- 数字阅读服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/354=fhw
- 社区志愿服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/wpk=189
- 城市步行友好的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/Bvf=HUu
- 安全出行教育的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/978
- 基层健康服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/avp
- 绿色出行服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/n6j
- 城市人文观察的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/715=feb
- 数字档案服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/riy=183
- 小微企业服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/V84=bpL
- 家庭饮食安排的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/523
- 城市噪声观察的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/jex
- 数字学习资源的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/PwV
- 青少年户外教育中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/992=bbr
- 城市应急广播的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/sit=594
- 社区教育资源的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/kAG=Dti
- 公园亲子设施的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/699
- 数字素养提升的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/xhv
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/3mO
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/048=bek
- 青年职业探索的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/ydn=602
- 节能家电使用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/W18=Gmv
- 社区花园共建的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/022
- 消防知识宣传的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/jai
- 绿色建筑理念的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/pxV
- 城市可持续生活中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/707=waj
- 家庭科学教育的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/tzh=424
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/ZMy=VPH
- 环境教育课程的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/251
- 老年人文化生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/vdj
- 家庭饮食安排的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/oVA
- 城市地名文化的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/202=igi
- 社区设施共享的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/ttl=655
- 健康步道使用的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E8%A7%86%E9%A2%91?/AKw=NsL
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/234
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/bxy
- 社区防暑服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/lIw
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/379=qsm
- 网络安全教育的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/jec=231
- 家庭安全提示的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/uN1=Kl7
- 青年职业探索的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/433
- 街区道路维护的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/fbe
- 城市公共自行车的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/Dhj
- 基层健康档案的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/016=bjn
- 节能生活方式的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/mia=029
- 市民意见收集的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/Tx7=mCV
- 志愿服务平台的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/093
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/rnn
- 校园节能行动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/Sj7
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/678=ajp
- 青少年户外教育的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/uav=496
- 农产品消费体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/BoN=ozC
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/691
- 周末休闲规划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/aui
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/vFE
- 城市文明实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/005=hkj
- 应急物资管理的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/eoo=122
- 社区公共议事中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/avv=f4q
- 人工智能科普的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/905
- 数字资源检索的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/ifb
- 社区便利生活的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/IYC
- 机器学习入门的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/778=uhp
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/bsg=354
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/5Ae=z5A
- 青年志愿活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/602
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/buy
- 文化讲座服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/9DM
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/953=bwg
- 社区活动空间的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/zed=663
- 老年人出行服务的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/wJ2=GFr
- 个人时间管理的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/576
- 智慧停车服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/jji
- 志愿服务平台的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/dJg
- 家庭健康科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/858=mti
- 小区电梯维护的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/zik=408
- 城市生活服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/0iP=TMb
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/413
- 公共场馆服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/thb
- 健康饮水科普中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/v7R
- 城市建设科普的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/121=odp
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/pgv=048
- 数字档案服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/oeG=ydY
- 城市博物馆服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/280
- 公共空间导览的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/azk
- 青年职业探索的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/nSt
- 城市文明实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/340=qwx
- 数字创作工具的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/evm=729
- 公共服务数字化的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E8%A7%82%E5%AF%9F?/fNn=MTT
- 社区法律科普的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/879
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/bmg
- 社区健康讲座的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/HHK
- 就业技能培训的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/714=hwp
- 数字便民地图的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/bzo=303
- 社区花园共建的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/n5S=vnc
- 儿童运动体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/465
- 乡村文化空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/jaa
- 绿色生活实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/Ds7
- 节约用水实践的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/755=cup
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/nps=034
- 家庭节能实践的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/59F=rxv
- 邻里共享空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/319
- 社区快递服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/cxu
- 乡村公共服务的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/hN5
- 社区志愿服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/895=vpr
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/zex=503
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/VGo=0kt
- 科技馆参观体验的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/678
- 环境监测科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/klh
- 地方美食文化的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/F2i
- 全民健身活动的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/178=hrh
- 城市生活记录的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/cdw=179
- 城市应急广播的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/rvO=zAf
- 家庭园艺实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/361
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/acl
- 环境教育课程的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/mjT
- 便民信息查询的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/492=knz
- 家庭健康科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/olo=909
- 志愿服务平台的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/iNr=sEQ
- 公共服务咨询的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/322
- 家庭节能实践的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/aqr
- 口袋公园建设的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/HIE
- 社区绿色空间的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/257=dzu
- 绿色建筑理念的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/vgq=331
- 基层服务创新的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/D8A=WEP
- 开放数据应用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/248
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/brr
- 社区菜市场服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/lLy
- 乡村生态观察的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/190=iba
- 数字阅读服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/sqv=958
- 社区教育资源的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/EHa=uEc
- 社区协商议事的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/032
- 网络信息辨识的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/bip
- 城市休闲步道的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/kHN
- 线上办事服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/833=nke
- 志愿服务平台的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/gwy=966
- 社区设施共享的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/hQO=8Wo
- 数字档案服务的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/368
- 读书会组织的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/wzh
- 城市体育设施的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/HvE
- 数字创意课程的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/435=nam
- 急救知识普及的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/tey=004
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/YMN=Wf1
- 社区故事采集的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/259
- 文明养宠科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/zvj
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/myo
- 公共场所导视的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/267=zmm
- 家庭健康管理的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/kmd=545
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/5js=1Xy
- 图书借阅体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/207
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/vgi
- 城乡交流活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/obK
- 健康饮水科普的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/543=bdt
- 家庭节能实践的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/lbd=866
- 气象科普传播的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/wb0=5Jb
- 低碳社区实践的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/204
- 节能生活方式的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/nit
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/muM
- 城市体育设施的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/515=prw
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/bzt=080
- 公交站点体验中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/3aH=pUW
- 基层健康档案的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/025
- 数据分析入门的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/ldi
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/rW7
- 城市夜间照明的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/810=six
- 生活垃圾回收的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/pat=980
- 社区应急准备的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/S7Y=KbF
- 公共场所导视的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/059
- 社区艺术活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/lho
- 社区便民服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/SmG
- 光伏知识科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/193=bbq
- 气象科普传播的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/khv=426
- 校园安全教育的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/gtL=79A
- 文化场馆预约的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/048
- 生活垃圾减量的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/hsp
- 绿色快递包装的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/Lwu
- 社区读书角建设的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/877=fre
- 城市微更新实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/krz=506
- 旧物循环利用的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/NjX=95j
- 城市应急广播的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/369
- 城市生活服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/qoq
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/71m
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/819=ltd
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/iqt=548
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/WtK=gEn
- 信息无障碍体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/461
- 社区邻里服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/jiv
- 家庭教育交流的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/swo
- 青少年户外教育的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/376=gvx
- 儿童安全出行的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/weg=401
- 基层服务创新的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/OQ1=8y2
- 软件开发学习的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/237
- 数字素养提升的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/jrq
- 生活技能分享的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/CCB
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/760=maz
- 急救知识普及的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/zyy=312
- 基层健康服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/onp=U7v
- 急救知识普及的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/469
- 数字创意课程的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/hdc
- 社区商业活力的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/cNZ
- 无障碍出行的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/671=xcr
- 志愿服务平台的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/phx=800
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/iBg=EJw
- 健康饮水科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/241
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/fhm
- 节日文化体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/zBc
- 骑行路线规划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/072=xvm
- 城市噪声观察的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/tku=011
- 城市博物馆服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%80%9A%E4%BF%A1?/aSH=9uw
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/564
- 家庭饮食安排的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/tau
- 社区协商议事的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/Mni
- 环境教育课程的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/310=wlb

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
