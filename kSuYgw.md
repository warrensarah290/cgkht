# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/anu=633
- 小区停车协商的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%B2%BE%E5%87%86%E5%AE%9A%E4%BD%8D100%25_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/EOK=Psd
- 节日文化体验的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/932
- 社区快递服务的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/ljx
- 数据分析入门的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/GHn
- 数字课堂应用的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/794=tks
- 口袋公园建设的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/fax=716
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86100_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/i6F=TEh
- 公益活动组织的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/971
- 农贸市场环境的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/zno
- 光伏知识科普的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/4xc
- 社区艺术活动的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/434=asi
- 乡村生态旅游的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/bhn=143
- 社区消防演练的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_3d%E6%9C%80%E5%87%86%E4%B8%AD%E5%A5%96%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/OuX=0i7
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/237
- 社区菜市场服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/pyq
- 生活垃圾回收的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/mXI
- 电动汽车充电的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/411=psu
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/cze=938
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_3d%E9%80%89%E5%8F%B7%E8%BF%87%E6%BB%A4%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/l6d=qsK
- 开放式学习空间的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/403
- 老年人文化生活的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/dil
- 绿色办公实践的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/NOA
- 绿色建筑理念的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/651=lhe
- 健康步道使用中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/chc=504
- 本地历史资料的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%B9%BF%E4%B8%9C11%E9%80%895%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/oac=mAm
- 城市文明出行的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/825
- 公共文化活动的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/gsg
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/68A
- 健康步道使用的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/881=xtc
- 健康饮食教育的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/zyi=139
- 地方民俗记录的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%81%9C%E5%94%AE_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/Tbk=I7O
- 社区文化节活动的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/718
- 公共服务沟通的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/whx
- 城市应急广播的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/sdN
- 新能源出行的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/140=kir
- 城市生活记录的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/eyb=455
- 公共场馆服务的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_15%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E9%AB%98%E6%89%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/kRc=OWf
- 节能生活方式的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/905
- 青少年编程学习中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/jxu
- 社区商业活力的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/8lH
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/344=gsm
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/faf=712
- 数字地图应用的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%9420%E5%88%86%E9%92%9F%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/2uC=QZW
- 公交无障碍服务的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/520
- 城市可持续生活的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/xms
- 城市微更新实践的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/sZ1
- 绿色办公实践的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/323=oty
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/seh=630
- 劳动教育实践的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%BF%E4%B8%9C%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/TuN=P4o
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/169
- 公园亲子设施的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/ilh
- 城市公共自行车的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/TzR
- 智能手机助老的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/386=wfn
- 人工智能科普的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/qro=699
- 社区活动报名的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%BF%E4%B8%9C%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/Ozy=Ver
- 社区健康讲座的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/040
- 城市骑行环境的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/ikv
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/dU6
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/282=llv
- 家庭网络使用的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/hea=602
- 公共空间导览的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/RjE=NFV
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/853
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/zrq
- 城市骑行环境中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Jah
- 居民健康教育的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/320=txx
- 垃圾分类指导的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/jlc=576
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%80%80%E5%B8%82_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/MX7=ySj
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/740
- 数字创作工具的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bjt
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/5No
- 社区文化传播的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/534=kfj
- 社区法律科普的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jls=996
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E5%BC%80%E5%A5%96_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uGE=Aa1
- 基层医疗预约的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/829
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/nwb
- 家庭食品保存的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/2hI
- 生活垃圾减量的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/280=nqs
- 市民意见收集的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/poi=054
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/Gpc=gyQ
- 社区养老服务的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/411
- 城市社区治理的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/hzq
- 运动安全知识的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/2T6
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/871=mdq
- 在线学习体验的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/dcj=820
- 公共场所导视的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_11%E9%80%895%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/ce4=PbL
- 家庭节能设备的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/650
- 社区商业活力的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/rjn
- 生活技能分享的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/z6P
- 公共服务指南的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/180=dpr
- 老年友好服务的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/fap=089
- 城市公共厕所中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_11%E9%80%895%E8%B5%9A%E5%B0%8F%E9%92%B1%E7%A7%98%E8%AF%80_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/Lfl=w02
- 家庭安全提示的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/941
- 家庭健康科普的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/mxo
- 急救知识普及中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/Ck7
- 社会体育指导的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/509=wnt
- 城市绿色交通的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/wxq=368
- 城市可持续生活的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/0kZ=OeM
- 社区防暑服务的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/168
- 新能源知识普及的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/amd
- 节气饮食文化的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/PFO
- 家庭环保行动的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/950=qgx
- 青年志愿活动的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/jei=887
- 青少年科技社团的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/dc4=M4I
- 开放数据应用的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/930
- 青少年户外教育的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/ezh
- 无障碍出行的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/TRq
- 低碳社区实践的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/691=mfx
- 食品安全科普的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/njl=263
- 城市应急科普的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_11%E9%80%895%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E4%B8%AD%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/cSm=7pZ
- 市民热线服务的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/380
- 机器人科普活动的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/jcl
- 就业技能培训的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/ZtH
- 健康饮水科普的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/045=iti
- 乡村文化活动的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/keb=796
- 生活技能分享中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/SWw=Aqd
- 邻里共享空间的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/523
- 便民服务地图的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/gim
- 网络安全教育的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/ZB6
- 网络安全教育的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/582=kfw
- 乡村生态观察的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/zhf=564
- 数字资源检索的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_11%E9%80%895%E8%B5%9A%E9%92%B1_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/cVB=fDS
- 数字地图应用的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/199
- 家庭网络使用的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/zzo
- 城市夜间生活的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/BmC
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/785=uvh
- 社区信息发布中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/ydu=356
- 城乡公共服务的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_11%E9%80%895%E5%82%BB%E7%93%9C%E5%BC%8F%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/bGs=nV3
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/102
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/uev
- 社区慢性病防控的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/qfa
- 科普展览体验的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/628=gpz
- 青少年心理健康的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/wtx=828
- 数字学习资源的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_11%E9%80%895%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/bIq=JqK
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/586
- 公交站点体验的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/jcl
- 社区运动空间的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/Khn
- 城市骑行环境的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/638=xuj
- 城市公共座椅的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/cei=891
- 数字便民地图的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%87%E8%83%BD6%E7%A0%8140%E6%B3%A8_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/bU3=GqF
- 社会体育指导的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/000
- 数字政务体验的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/ulo
- 城市地名文化的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/JF4
- 社区文化节活动的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/608=lva
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/zrm=955
- 节日文化体验的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E8%81%8C%E4%B8%9A11%E9%80%895%E9%AB%98%E6%89%8B%E4%B9%B0%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/KJU=3m8
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/594
- 地方戏曲体验的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/lch
- 家庭消费规划的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/YgJ
- 城市适老服务的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/346=woi
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/eks=047
- 地方美食文化中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A9%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/5Qu=Ujl
- 社区共享书架的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/241
- 新能源出行的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/aob
- 家庭急救准备的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/rKb
- 地方旅游导览的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/100=flo
- 生活服务数字化的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/dxl=849
- 城市公共标识的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_11%E9%80%895%E6%9D%802%E4%B8%AA100%25%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/vQ1=tIH
- 城市公共饮水的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/185
- 社区生活指南的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/kja
- 家庭照护支持的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/zwv
- 全民阅读推广的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/513=ztv
- 数字创意课程的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/srh=690
- 社区家政服务的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_11%E9%80%89%E4%BA%94%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E5%9B%BE_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/J7m=LCE
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/508
- 软件开发学习的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/ozk
- 家庭运动计划的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/Pud
- 社区信息发布的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/596=bxg
- 公共服务预约的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/osp=384
- 个人信息保护的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_11%E9%80%895%E7%AC%AC%E4%B8%80%E4%BD%8D%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/SAO=0Bh
- 公园休闲体验的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/740
- 城市微更新实践的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/ezr
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/V61
- 校园社团活动的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/966=vny
- 街道综合服务的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/dct=765
- 光伏知识科普的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_11%E9%80%895%E4%BB%BB%E9%80%892%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%8A%95%E8%B5%84?/Mtm=cJ0
- 个人数据管理的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/724
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/vpa
- 药品使用科普的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/oZ9
- 农业科普体验的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/221=okv
- 电动汽车充电的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/cbw=181
- 智慧城市体验的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/luD=0p9
- 城市雨天出行的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/012
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/gun
- 社区商业活力的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/MLm
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/473=nis
- 城市文明实践的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/mus=138
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_11%E9%80%895%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/Oll=Pmi
- 社区交通安全的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/153
- 社区运动空间的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/qzg
- 城市步行环境的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/nw5
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/223=zqh
- 城市基础设施的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/vjj=274
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_11%E9%80%89%E4%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E5%85%A8%E5%9B%BD%E5%81%9C%E5%94%AE_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/pWr=tF2
- 食品配送体验的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/516
- 口袋公园建设的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/uxg
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/FwY
- 社区知识分享的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/663=gqf
- 社区教育资源的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/lla=799
- 公共文化活动的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E4%B8%AD%E4%B8%89%E4%B8%AA%E5%A4%9A%E5%B0%91%E9%92%B1_%E5%BE%97%E7%89%A9%E5%88%B8%E5%95%86?/KaT=bnW
- 家庭急救准备的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/738
- 社区科普课堂的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/wvf
- 节能家电使用的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/BXc
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/288=ywf
- 社区信息发布的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/zbb=380
- 城市公共艺术的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%8D%81%E4%B8%80%E9%80%89%E4%BA%94%E4%BB%BB3%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E5%BF%85%E4%B8%AD_%E7%99%BE%E5%BA%A6%E7%BA%AA%E5%AE%9E?/xTC=5a9
- 街区更新实践的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/143
- 家庭节能实践的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/zvc
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/Xsz
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/953=wtf
- 乡村公共阅读的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/xop=598
- 老年友好服务的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%9B%9B%E4%B8%AA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/SD1=EOJ
- 社区科普课堂的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/036
- 儿童安全出行的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/wdp
- 社区活动策划的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/LK3
- 家庭节能实践的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/574=cel
- 数字公共文化的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/xbu=548
- 社区休闲设施的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E6%8C%82%E6%9C%BA%E8%B5%9A%E4%B8%80%E5%A4%A980%E5%85%83_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/GAt=GrQ
- 社区防暑服务的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/864
- 社区手工活动的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/sft
- 儿童友好空间的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/M4R
- 街区更新实践中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/288=uub
- 社区健康讲座的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/xyq=186
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_11%E9%80%895%E7%A8%B3%E8%B5%9A%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/rsG=7Fq
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/614
- 信息无障碍体验的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/hba
- 公园休闲体验的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/mwX
- 社区家校合作的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/159=rwj
- 通勤路线规划的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/eht=788
- 城市地名文化的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94%E7%9A%84%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/Lom=rkA
- 社区便利生活的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/324
- 终身学习资源的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/rkc
- 在线学习体验的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/bwP
- 社区老年食堂的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/111=gvf
- 城市展览体验的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/dkv=586
- 健康饮食教育的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/lRh=8Bt
- 旧物循环利用的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/807
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/nzp
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/DeB
- 公园亲子设施的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/409=ela
- 消防知识宣传的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/cbd=353
- 老年友好服务的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/9ZJ=oSj
- 数字便民地图的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/631
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/msf
- 城市绿道建设的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/RqX
- 骑行路线规划的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/089=pmz
- 地方美食文化的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/xim=649
- 数字阅读服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/998=DdX
- 数字学习资源的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/483
- 口袋公园建设的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/nvt

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
