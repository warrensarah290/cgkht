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

- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/nzg=572
- 社区托育服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/lti=5tG
- 基层服务创新的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/751
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/pwp
- 社区便民服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/Pm2
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/103=kkp
- 本地消费场景的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/qwh=585
- 旧物循环利用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/0my=dwk
- 非遗课堂体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/538
- 网络安全教育的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/rwx
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/M2v
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/130=dnd
- 城市公共艺术的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/ubj=916
- 公共服务指南的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%A6%81%E9%97%BB?/YtU=MYl
- 城市公共饮水的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/256
- 农贸市场环境的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/emb
- 居家防滑改造的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/xUm
- 数字地图应用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/296=qzh
- 邻里共享空间的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/mbo=997
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%81%A5%E5%BA%B7?/aI5=FjW
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/130
- 终身学习资源的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/mjo
- 图书借阅体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/huR
- 社区消防演练的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/465=ktj
- 网络安全教育的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/zrl=141
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/Dmz=hkS
- 街道综合服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/954
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/gzp
- 周末休闲规划的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/nMO
- 居民健康教育的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/716=rrg
- 健康饮食教育的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/haq=140
- 城市雨天出行的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_360%E8%B5%84%E8%AE%AF?/k0K=ePc
- 生成式工具使用的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/768
- 生活服务数字化中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/szm
- 学校食育活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/2Md
- 城市应急广播的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/452=bcs
- 学校食育活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/euv=443
- 创业经验分享的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/5ir=ITm
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/446
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/dcs
- 便民服务地图的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/55S
- 安全出行教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/655=odj
- 开放式学习空间的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/pvp=509
- 居民健康教育的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/n5f=kkt
- 社区便民集市的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/429
- 人工智能科普的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/qdi
- 医院导诊服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/Y6U
- 街头绿植养护的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/228=qda
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/keq=641
- 数字生活课堂的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E5%93%94%E5%93%A9%E8%B4%A2%E6%8A%A5?/6ij=Ohy
- 本地消费场景的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/349
- 街区小店体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/dpq
- 邻里互助活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/Qoc
- 文化讲座服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/678=xph
- 城市文明出行的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/koy=667
- 本地消费场景的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-IOS%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/Nt7=hS0
- 气象科普传播的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/510
- 地方戏曲体验的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/otd
- 社区垃圾回收的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/ukh
- 骑行路线规划的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/214=ubf
- 社区公共卫生的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/ily=393
- 社区活动策划的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/rsq=RXz
- 科学信息获取的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/909
- 电动汽车充电的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/jtw
- 儿童阅读角的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/LSc
- 科学运动指导的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/021=yqn
- 社区安全巡查的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/jhn=126
- 社区共享书架的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/khZ=3jR
- 公共空间休憩的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/704
- 智慧停车服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/vqm
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/eOz
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/571=omx
- 地方美食文化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/opm=294
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E4%B8%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/5bx=cVH
- 城市文明出行的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/812
- 健康步道使用的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/psr
- 气象科普传播的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/Yq4
- 智能家居应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/941=esu
- 数字课堂应用的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/fqy=810
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%BD%A9%E7%BD%91--%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%85%AC%E5%91%8A?/eDw=zYs
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/424
- 生活技能分享的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/pmh
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/Vbo
- 日常摄影记录的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/121=dsd
- 老年数字阅读的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/gza=350
- 城市人文观察的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91--%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/lfP=oeK
- 个人数据管理的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/711
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/nsn
- 家庭运动计划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/WmD
- 社区快递服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/010=wfs
- 邻里互助活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/abq=589
- 城市绿道建设的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%AE%9D%E8%B4%9D--%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/a98=lnE
- 城市公共自行车的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/153
- 图书借阅体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/wil
- 城市慢行系统的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/z19
- 消防知识宣传的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/088=vap
- 医院导诊服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/ydf=290
- 家庭运动计划的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%AB%9E%E5%BD%A9%E7%BD%91--%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/h5j=MeU
- 城市慢行系统的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/236
- 健康步道使用的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/vqj
- 乡村公共服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/OAH
- 公共卫生设施的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/950=uso
- 社区文化节活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/eaa=459
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/6xQ=1QL
- 公共场馆服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/067
- 全民健身活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/wtc
- 青年职业探索的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/fI3
- 城市文化路线的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/462=mkj
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/cee=925
- 社区防暑服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8--%E7%BD%91%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/FvR=zaS
- 绿色办公实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/603
- 机器人科普活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/fls
- 社区共享书架的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/1D9
- 城市体育设施的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/326=bup
- 街道综合服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/axs=214
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91--%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/u3S=2k2
- 图书借阅体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/281
- 城市文明实践的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/jae
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/3L8
- 青少年心理健康中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/256=jtn
- 家庭环保习惯的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/djr=579
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E5%BD%A9%E7%BD%91--%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/PdI=gaM
- 街区更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/738
- 家庭理财科普的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/tnn
- 儿童阅读角的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/FiA
- 社区老年食堂的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/380=suv
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/zgq=715
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%AE%9A%E7%89%9B--%E6%89%8B%E6%9C%BA%E7%AB%AF%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/vga=HMW
- 家庭收纳实践的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/101
- 城市微更新实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/sql
- 街道综合服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/cNW
- 开源技术交流的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/745=pak
- 城市空气科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/qen=477
- 城市社区治理的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E5%AE%A2%E7%BD%91--%E6%89%8B%E6%9C%BA%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%AE%89%E9%98%B2?/W8S=KEv
- 城市休闲步道中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/354
- 城市体育设施的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/ntu
- 城市便民驿站的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/oo1
- 公共文化活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/391=aqd
- 公益活动组织的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/pon=568
- 公共服务咨询的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E9%92%9F%E5%BD%A9%E5%9C%A8%E7%BA%BF--APP%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/jDL=jnj
- 乡村公共文化中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/220
- 公共文化活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/yvh
- 非遗课堂体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/Rw5
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/807=jzo
- 药品使用科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/iea=357
- 社区环保活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%BD%91--APP%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/hzb=yMS
- 社区设施共享的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/892
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/plt
- 非遗体验活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/VWp
- 街区道路维护的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/410=dlj
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/isq=206
- 社区手工活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9--%E5%AE%98%E6%96%B9APP_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/fdU=cyP
- 城市文化路线的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/586
- 小微企业服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/rwz
- 社区公共卫生的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/eTZ
- 社区体育组织的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/089=hdz
- 社区停车服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/uyu=409
- 健康步道使用中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A82%E5%85%83--APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/zkD=WTJ
- 在线教育体验的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/599
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/cwa
- 城市空气科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/KUy
- 城市水环境观察的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/623=jol
- 本地消费场景的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/pox=492
- 小微企业服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A9%E9%BD%90%E7%BD%91--%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/mrn=r7J
- 家庭安全提示的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/555
- 家庭运动计划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/vfq
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/T9w
- 城市雨天出行的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/813=wbb
- 社区公共议事的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/apl=276
- 开源技术交流的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8E%A7--%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/jAj=Gzn
- 乡村公共文化的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/226
- 日常摄影记录的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/qrs
- 开源技术交流的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/n6I
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/662=dqf
- 社区绿色空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/srd=791
- 社区庭院绿化的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BC%80%E5%A5%96%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/EFs=wX7
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/775
- 城市文明出行的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/wvi
- 社区运动空间中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/XJv
- 家庭教育交流的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/248=tmh
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/dxs=670
- 创业经验分享的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E7%88%B1%E5%BC%80%E7%BD%91--%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/scX=EkM
- 运动安全知识的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/503
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/oqz
- 智慧城市体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/A14
- 公共空间照明的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/696=rsz
- 本地消费场景的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/jpe=532
- 街区绿化养护的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%99%BA%E6%85%A7%E5%BD%A9--%E5%AE%98%E6%96%B9%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/JRE=l4a
- 生活垃圾回收的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/778
- 科技馆参观体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/mhz
- 新能源出行的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/sEh
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/355=tqh
- 家庭健康科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/mwy=748
- 传统手工艺体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BF%B7--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/LJq=o2Z
- 乡村阅读空间的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/851
- 社区商业活力的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/jej
- 城市共享单车的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/M5u
- 社区应急准备的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/969=uxv
- 校园阅读活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/caj=188
- 乡村生活观察的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BF%A1%E6%81%AF%E7%BD%91--%E5%AE%98%E6%96%B9%E4%BF%A1%E6%81%AF%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/yK0=DI5
- 绿色办公实践的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/983
- 公园亲子设施的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/qsb
- 气象科普传播的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rhP
- 数字政务体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/543=xme
- 社区知识分享的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/erz=152
- 公共服务预约的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%BB%8F%E7%BD%91--%E5%AE%98%E6%96%B9%E6%9C%8D%E5%8A%A1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/IhH=DWz
- 社区家校合作的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/094
- 社区手工活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/ndx
- 数字政务体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/I7j
- 公共空间导览的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/684=eqe
- 公共服务数字化的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/lot=365
- 家庭运动计划的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%8B%E7%BD%91--%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/jE8=chN
- 社区老年食堂的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/687
- 公共服务数字化的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/qmt
- 城市体育设施中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/UBO
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/694=tnz
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/vph=020
- 安全出行教育的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91--%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/iMZ=Wle
- 社区故事采集的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/159
- 网络安全教育的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/jsw
- 公共交通接驳的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/Xem
- 地方美食文化的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/637=igo
- 居家适老化改造中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/gjz=046
- 社区交通安全的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%8F%8B%E7%BD%91--%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/aGU=h7i
- 农业科普体验的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/570
- 个人信息保护的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/jxx
- 公共文化活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/pCo
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/737=rfs
- 城市公共自行车的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/udc=074
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6--%E9%A6%96%E9%A1%B5%E5%AF%BC%E8%88%AA%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%90%86%E8%B4%A2?/YfN=4HA
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/460
- 旧物循环利用的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/wnw
- 儿童阅读角的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/e3x
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/436=kbh
- 居家适老化改造中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/sut=235
- 绿色生活实践的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%A2%91%E9%81%93--%E7%94%A8%E6%88%B7%E5%85%A5%E5%8F%A3_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/bII=Bya
- 公共服务评价中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/583
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/zrp
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/NxK
- 公共空间照明的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/973=ric
- 人工智能科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/say=969
- 社区休闲设施的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B5%84%E8%AE%AF%E7%BD%91--%E4%BC%9A%E5%91%98%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%96%B0%E9%97%BB?/NTU=H7z
- 校园阅读活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/127
- 人工智能科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/add
- 公共空间照明中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/9Gp
- 城市绿道建设的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/503=khj
- 城市体育设施的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/euf=470
- 农业科普体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%95%B0%E6%8D%AE%E7%BD%91--%E8%B4%A6%E6%88%B7%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/oXs=nTt
- 基层健康档案的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E7%BD%91--%E8%B4%A6%E5%8F%B7%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/393
- 运动安全知识的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2%E7%BD%91--%E8%B4%A6%E5%8F%B7%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/zcv

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
