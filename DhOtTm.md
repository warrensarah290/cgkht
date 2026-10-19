# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 城市步行环境的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/oyn=915
- 开源技术交流的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/8PQ=lI0
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/043
- 街区道路维护的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/tps
- 家庭网络使用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/xKy
- 社区设施共享的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/032=egx
- 家庭安全提示的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/ikv=187
- 街道综合服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/MhP=7Mf
- 社区垃圾回收的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/612
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/nnl
- 街道综合服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Ebz
- 公共服务指南的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/888=ekk
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/fzc=843
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qGz=wl4
- 乡村休闲旅游的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/858
- 环境监测科普的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/nnf
- 文明养宠科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/siz
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/871=uvx
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/eqw=863
- 本地历史资料的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/17H=gyc
- 软件开发学习的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/277
- 文明养宠科普的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/jig
- 乡村公共文化的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/ovn
- 社区公共卫生的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/078=qwq
- 个人信息保护的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/euz=491
- 社区文化节活动的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/kdN=PXJ
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/374
- 光伏知识科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/mgv
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/Hny
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/573=wfi
- 儿童阅读角的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/wbd=225
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/zud=nLx
- 租房信息服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/027
- 校园安全教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/kxe
- 食品配送体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/3as
- 健康步道使用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/949=wga
- 家庭健康科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/zny=665
- 社区活动空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/5US=BuC
- 邻里共享空间的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/362
- 街区道路维护的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/nrn
- 健康饮食教育的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/HQU
- 公共空间照明的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/659=suy
- 青年职业探索的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/ura=810
- 市民意见收集的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/hup=ImP
- 街区更新实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/191
- 线上阅读资源的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/lsu
- 老年友好服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/nrS
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/166=zab
- 远程协作工具的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/frd=580
- 城乡公共服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E6%90%9C%E7%8B%90%E6%95%B0%E8%AF%BB?/yKm=jUH
- 健康饮水科普的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/352
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/nrj
- 社区活动空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/PGc
- 环境教育课程的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/860=jva
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/gnr=282
- 青少年编程学习中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/KXZ=l9X
- 城市应急科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/180
- 小区电梯维护的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/hpt
- 数字公共文化的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/jUC
- 城市博物馆活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/629=aaa
- 社区垃圾分类的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/ego=568
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/OMQ=7rt
- 健康饮水科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/556
- 校园安全教育的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/rfn
- 家庭健康科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/s28
- 家庭网络使用的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/886=gqo
- 居民健康教育的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/rva=058
- 开放式学习空间的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/v5g=egS
- 智能家居应用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/683
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/tnu
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/txr
- 全民健身活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/368=tdr
- 社区科普课堂中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ago=899
- 老年人日常照护的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gYb=Bml
- 公共设施使用的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/212
- 软件开发学习的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/jju
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/ajj
- 城市博物馆活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/757=inz
- 智慧城市体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/zca=254
- 家庭收纳实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/DwF=9SJ
- 社区学习活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/137
- 社区花园共建的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qtq
- 食品配送体验中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/5E6
- 城市适老服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/366=svj
- 城市生活服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tbk=680
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jIh=DG4
- 家庭环保行动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/129
- 城市水环境观察的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/ddh
- 家庭安全提示的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/n3J
- 开放式学习空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/529=vov
- 儿童户外活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/mtm=001
- 社区互助网络的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%9C%9F%E8%B4%A7?/tnZ=HDC
- 数字档案服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/417
- 电子商务服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/ptc
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/RWb
- 城市生活记录的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/137=xbm
- 社区故事采集的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/glr=698
- 社区安全巡查的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E4%BC%97%E6%B5%8B?/0Sg=5Rh
- 公共服务沟通的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/414
- 城市应急广播的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/pgb
- 家庭急救准备的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/8e0
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/170=fmh
- 地方民俗记录的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/equ=203
- 环境教育课程的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/jlz=MjZ
- 公园休闲体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/698
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/aog
- 文化场馆预约的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/lzR
- 社区防暑服务的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/710=cif
- 社区运动空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/vay=334
- 乡村生态观察的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/yqo=svQ
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/848
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/wqc
- 居家适老化改造的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/sQD
- 家庭节能设备的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/889=yfi
- 小区电梯维护的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/enr=053
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/281=GIL
- 公共空间照明中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/939
- 乡村电商实践的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/hlq
- 文化讲座服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/ZBR
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/433=vrn
- 社区体育组织中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/kje=118
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/Pbm=89O
- 城乡公共服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/458
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/nzj
- 生活服务数字化的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/OUS
- 公共卫生设施的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/829=wov
- 家庭节能实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/oij=605
- 休闲运动入门的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/SDC=jd0
- 家庭饮食安排的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/268
- 城市公共空间的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/vnu
- 租房信息服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/KjY
- 志愿者培训交流的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/525=wng
- 运动安全知识的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/xqx=702
- 本地历史资料的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/MXz=g1u
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/698
- 校园节能行动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/yzm
- 街区更新实践的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/inz
- 小区公共照明中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/238=pla
- 公交无障碍服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/kqu=900
- 便民服务窗口的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/cuD=GCn
- 公交站点体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/541
- 社区信息发布的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/ffu
- 智能手机助老的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/2TQ
- 地方戏曲体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/120=dpm
- 社区花园共建的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/dpt=484
- 终身学习资源的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/W0k=gwv
- 小区停车协商的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/790
- 儿童户外活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/umo
- 口袋公园建设的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/wUl
- 数字支付体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/388=sio
- 社区生活指南的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/pxa=982
- 社区故事采集的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/u4i=HgP
- 开放数据应用的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/050
- 城市慢行系统的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/jyz
- 青少年科技社团的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/ZuU
- 城市绿道建设的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/545=vxi
- 社区艺术活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/bsy=222
- 数字公共文化的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/WyW=Ve4
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/891
- 校园节能行动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/wra
- 城市适老服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/q1c
- 课后服务体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/424=eet
- 学校体育活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/wrl=835
- 城市夜间照明的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/0JO=ajG
- 基层健康档案的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/632
- 社区便民集市的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/tjg
- 小区电梯维护的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/B9f
- 家庭安全提示的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/304=fff
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/rcp=668
- 运动安全知识的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/C5N=Sas
- 节能家电使用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/644
- 家庭教育交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/vgb
- 科普展览体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/6f9
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/057=tij
- 网络安全教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/yky=981
- 城市住房服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/s6q=rsd
- 食品配送体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/324
- 小微企业服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/pbs
- 家庭教育交流的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/mQP
- 口袋公园建设中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/415=xfk
- 健康信息获取的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/cgx=186
- 城市生活服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_500%E4%B8%87%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/jai=E9O
- 机器学习入门的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/127
- 城市公共饮水的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/qhl
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/gJE
- 城市应急科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/606=xgu
- 电动汽车充电的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/zji=748
- 食品安全科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/V73=nBq
- 城市人文观察的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/584
- 社区设施共享的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/gjx
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Qjx
- 社区托育服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/285=btx
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tnf=780
- 公园无障碍服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/bvd=6ZI
- 青少年科普实践的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/726
- 机器人科普活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/pez
- 休闲运动入门的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/893
- 城市公共饮水的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/570=paf
- 数字艺术创作的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/wvk=799
- 乡村阅读空间的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/6er=yUn
- 无障碍出行的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/791
- 居民健康教育的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/cfj
- 社区公共议事的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/uoO
- 公共交通信息服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/958=ghr
- 新能源出行的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/rwo=092
- 社区活动报名的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/F2b=IrO
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/777
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/elb
- 乡村教育资源的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/kUn
- 基层服务创新的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/901=uyd
- 便民服务窗口的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/dia=010
- 家庭环保习惯的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/db1=oe0
- 城市共享单车的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/184
- 绿色出行服务的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/ohm
- 生活技能分享的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/lMx
- 城市空气科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/010=yme
- 社区安全巡查的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/bfr=493
- 家庭节能实践的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/SEW=j1Q
- 社区体育组织的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/971
- 全民健身活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/uay
- 城市共享单车的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/6Ht
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/140=pwq
- 电子商务服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/jyj=794
- 社区垃圾分类的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E4%B8%87%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/L1H=Fep
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/482
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/uxk
- 城市地名文化的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/6Vn
- 老年友好服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/333=dzp
- 公共服务咨询的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/ali=710
- 绿色办公实践中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E5%8C%BA?/srl=T3Y
- 儿童安全出行的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/571
- 城市文明出行的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/xaf
- 公共文化活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/cyg
- 社区信息发布的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/133=slk
- 在线学习体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/zzr=650
- 社区信息发布的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_500%E4%B8%87%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/l2L=rZH
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/126
- 城乡交流活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/fbg
- 邻里互助活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/6kP
- 城市文明实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/118=xav
- 社区便利生活的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/gpn=326
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_1588cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/ZNa=9Gf
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/073
- 社区活动空间的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/ktd
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/Rvr
- 生成式工具使用的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/577=ryy
- 绿色消费选择的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/szb=248
- 便民维修服务的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_1588cc-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/q4m=JjD
- 数字生活课堂的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1588cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/892
- 绿色办公实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1588cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/oww

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
