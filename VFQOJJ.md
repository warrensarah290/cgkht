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

- 城市公共饮水的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/380
- 城市骑行环境的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/iai
- 城市空气科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/uRT
- 社区学习活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/708=syj
- 数字生活课堂的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/bgg=131
- 公共服务数字化的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/lBa=7ER
- 社会体育指导的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/936
- 传统节日科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/dui
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Asu
- 青少年户外教育的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/462=hgf
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/lnx=920
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/ioi=P3w
- 绿色建筑理念的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/563
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/bgg
- 数字档案服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/nR5
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/035=zit
- 新能源出行的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/mfx=678
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/2Ka=y7F
- 开源技术交流的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/495
- 社区交通安全的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/glw
- 地方民俗记录的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/3Sp
- 职业技能学习的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/193=kea
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/hue=348
- 绿色快递包装的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/7pC=bvN
- 社区手工活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/545
- 文化讲座服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/dvg
- 生活垃圾减量的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/DwO
- 基层健康档案的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/476=asc
- 学校体育活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/crf=784
- 乡村文化空间的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/you=Q4y
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/074
- 健康步道使用的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/dms
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/jPI
- 安全出行教育的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/231=zdx
- 周末休闲规划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/kbc=268
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0vi-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/Gba=CnO
- 乡村生活观察中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/768
- 医院导诊服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/fyd
- 城市基础设施中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/Au2
- 科学信息获取的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/796=wlt
- 便民服务地图的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/jvj=640
- 口袋公园建设的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0vi-APP_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/G34=ZSI
- 生活技能分享的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/400
- 社区活动策划的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/glp
- 数据分析入门的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/TBA
- 社区花园共建的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/936=wvc
- 数字档案服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/afz=331
- 科学运动指导的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0vi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/YEi=Www
- 社区知识分享的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/084
- 城市文明实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/hap
- 农业科普体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/er4
- 非遗课堂体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/487=cvp
- 食品配送体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/kmy=293
- 数据分析入门的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/ID3=Fkv
- 社区商业活力的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/290
- 青少年科技社团的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/ala
- 光伏知识科普的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/8Wg
- 社区体育组织的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/937=sov
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/qdr=960
- 社区便利生活的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0vi-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/lUm=NxE
- 机器学习入门的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/551
- 老年人日常照护的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/eij
- 家庭网络使用的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/Soq
- 青年职业探索的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/247=vut
- 家庭志愿活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/hkl=856
- 环境教育课程的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%87%A4%E5%87%B0vi-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/Pqq=Jz0
- 城市社区治理的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/514
- 社区菜市场服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/wjv
- 社区故事采集的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/lLP
- 公共服务数字化的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/661=htm
- 人工智能科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/znw=092
- 数据分析入门的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0vi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/xHJ=Pev
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/016
- 在线学习体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/uhz
- 城市夜间生活的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/G48
- 家庭消费规划的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/783=sre
- 社区协商议事的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/iax=831
- 基层健康档案的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0vi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/j6m=vNM
- 公共空间休憩的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/636
- 医院导诊服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/gny
- 基层健康档案的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/MAE
- 城市便民驿站的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/581=yiq
- 旧物循环利用的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/knw=627
- 就业技能培训的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0vi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/ux3=PD1
- 社会体育指导的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/069
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/llu
- 乡村电商实践的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/GN5
- 非遗体验活动中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/767=qye
- 社区应急准备的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/pmd=760
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/c4M=NLP
- 老年人文化生活中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/574
- 社区快递服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/cre
- 家庭用电安全的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/6IJ
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/237=zhn
- 图书馆数字服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/eon=178
- 课后服务体验的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%87%A4%E5%87%B0vi-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/EbY=j9Z
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/223
- 健康信息获取的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/uxy
- 租房信息服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/q8Z
- 城市适老服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/421=dyb
- 青少年编程学习的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/nxq=881
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0vi-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/x9A=mMs
- 社区互助网络的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/478
- 公共空间照明的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/eyo
- 公共服务数字化的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/XMv
- 职业技能学习的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/819=bmw
- 公共服务预约的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/ofs=189
- 环境教育课程的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/I5S=YWH
- 物业服务沟通的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/563
- 社区科普课堂的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vwl
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/K25
- 节假日出行安排的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/963=qqv
- 开放数据应用的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/fga=736
- 社区志愿服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/ddT=uhD
- 数字支付体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/392
- 老旧小区改造的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/pzh
- 租房信息服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/MUb
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/234=qgc
- 节假日出行安排的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/mtk=208
- 垃圾分类指导的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8E%BF%E5%9F%9F?/X3n=xV2
- 开源技术交流的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/134
- 数字政务体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/ggo
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/Hvo
- 开源技术交流的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/839=jza
- 数字支付体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/zvt=069
- 医院导诊服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/dRe=IHW
- 软件开发学习的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/024
- 社区邻里服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/iyb
- 城市水环境观察的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/k7Z
- 青年志愿活动的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/089=vkp
- 城乡交流活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/tzq=701
- 社区教育资源的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/Ylx=gqK
- 便民服务窗口的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/037
- 城市生活记录的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/jpe
- 街区更新实践的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/1jU
- 城市人文观察的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/483=hqy
- 学校体育活动的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/pez=849
- 地方旅游导览的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95welcome_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/I1I=hBt
- 小区停车协商的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/986
- 儿童安全出行中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/hyf
- 社区修缮行动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/f88
- 乡村阅读空间的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/073=ssp
- 公共卫生设施的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/qac=064
- 职业技能学习的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/OKq=G1D
- 社区活动空间的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/082
- 小区电梯维护的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/tac
- 无障碍出行的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/F0V
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/417=vrv
- 儿童友好空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/ipg=860
- 家庭用电安全的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/1EK=kxw
- 在线教育体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/683
- 城市文化路线的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/jbz
- 社区便民服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/LVE
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/028=gkl
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/ted=053
- 城市可持续生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/ZW2=sNM
- 社区协商议事的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/640
- 地方美食文化的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/dbg
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/vwD
- 城市公共饮水的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/766=efj
- 农村环境治理的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/qln=627
- 城市公共座椅的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%AE%9E%E5%BD%95?/unt=NXj
- 公共设施使用的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/974
- 公共空间休憩的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/pfw
- 社区便民集市的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/2aW
- 居家适老化改造的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/021=hgz
- 城市展览体验的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/dzu=168
- 市民热线服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E4%B8%8B%E8%BD%BD_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/fI6=X7c
- 社区垃圾回收的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/889
- 健康信息获取的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/jsq
- 社区邻里服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/sXS
- 本地消费场景的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/507=rni
- 周末休闲规划的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/gmv=153
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%87%A4%E5%87%B0-APP_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/HgS=Zmc
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/969
- 文化场馆预约的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/bhj
- 公共服务预约的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/Cs2
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/779=jdj
- 城市微更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/cdf=021
- 居民健康教育的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/7Tr=MYU
- 在线教育体验的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/961
- 家庭食品保存的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/bgn
- 城市共享单车的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/9qF
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/335=mzw
- 小区停车协商的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/qqf=401
- 社区艺术活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/FNI=5oY
- 公共服务预约的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/453
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/xtr
- 周末休闲规划的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/kFF
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/482=wea
- 老年运动活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/zsh=981
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/Mwn=sZ9
- 老年运动活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/822
- 城市适老服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/nve
- 乡村产业科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/vJw
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/924=wmj
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/bgl=559
- 科学教育活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/dHl=zOP
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/574
- 乡村文化空间的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/xms
- 数字支付体验的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/S7A
- 环境教育课程的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/336=nif
- 社区托育服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/ups=659
- 数字课堂应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/D7x=tkX
- 家庭用电安全的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/367
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/umv
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/nfE
- 家庭环保行动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/210=pef
- 灵活就业交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/ogm=659
- 社区快递服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/dLq=Pad
- 数字支付体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/436
- 本地消费场景的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/ntj
- 城市人文观察的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/EGo
- 图书馆活动策划的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/004=krb
- 环境监测科普的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/nfd=824
- 文化场馆预约的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%BA%93?/ZsU=KNR
- 绿色快递包装的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/640
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/guq
- 公交站点体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/Bgs
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/027=jjq
- 机器人科普活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/txh=264
- 家庭志愿活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%BC%AB%E8%AF%84?/r68=cfd
- 社区故事采集的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/825
- 科学健身方法的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/nce
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/ERI
- 儿童户外活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/253=zkb
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/blm=742
- 社区便利生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/09g=grV
- 通勤路线规划的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/619
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/wrm
- 社区庭院绿化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/YJ3
- 居家防滑改造的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/346=nfy
- 社区艺术活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/bjs=322
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%87%A4%E5%87%B0-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/IYS=zZK
- 城市住房服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/315
- 物业服务沟通的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/zej
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/EjY
- 基层医疗预约的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/901=uef
- 医院导诊服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/htj=908
- 家庭安全提示的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/xQc=aIy
- 公共场馆服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/707
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/plf
- 青少年科普实践的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/0NV
- 食品安全科普的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/181=nxi
- 社区花园共建的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/uwy=886
- 乡村文化空间中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/FyD=AeJ
- 社区停车服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/242
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/hoi
- 小区公共照明的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/v1C
- 地方旅游导览的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/991=vdg

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
