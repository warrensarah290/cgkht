# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 城市建设科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/bRQ
- 便民维修服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/656=yau
- 社区儿童活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/iwx=833
- 网络信息辨识的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_8258cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%A3%9F%E5%93%81?/f4K=ubo
- 非遗体验活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/040
- 急救知识普及的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/non
- 社区商业活力的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/fvW
- 家庭食品保存的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/309=jrq
- 家庭养老规划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/agg=676
- 青少年户外教育的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/L6P=0ng
- 数据分析入门中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/092
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/nck
- 家庭照护支持的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/1SN
- 校园社团活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/714=jps
- 校园节能行动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/ypq=740
- 校园节能行动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_506cc%E5%BD%A9%E7%A5%A8_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/eKH=4ax
- 社区便民集市的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/597
- 户外活动组织的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/bdz
- 节能生活方式的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/UxI
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/719=hcg
- 公共设施使用的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/tor=393
- 城市微更新实践的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E6%BE%B3%E9%97%A8%E5%BD%A98818_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/yqy=pUw
- 就业技能培训的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/419
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/mtn
- 社区便利生活的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/ZXm
- 公共场所导视的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/167=dtx
- 传统手工艺体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/mxg=019
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89?/tor=c57
- 读书会组织的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/458
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/vvq
- 城市公共厕所中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/Z5O
- 老年运动活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/364=vbp
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/kkv=851
- 城市展览体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1588cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/omB=oXY
- 科学观察活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/248
- 城市共享单车的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ywr
- 乡村产业科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/DrH
- 数据分析入门的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/060=jer
- 城市文明出行的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/rwn=529
- 社区邻里服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/apO=a5y
- 地方民俗记录的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/900
- 社区生活指南的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/vce
- 城乡公共服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/IGr
- 社区文化节活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/601=jfd
- 公共文化活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/lwq=507
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1588cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A6%81%E9%97%BB?/ojd=V7z
- 社区儿童活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/115
- 城市水环境观察的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/jdg
- 老年学习活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/Udz
- 社区防暑服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/787=swo
- 城乡公共服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/htm=251
- 城市应急广播的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1588cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/Z2w=hES
- 数据分析入门的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/367
- 数字课堂应用的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/hol
- 城市骑行环境的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/nK4
- 街区小店体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/423=rop
- 邻里共享空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/yyx=022
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_1588%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/7VP=5YQ
- 网络信息辨识的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/246
- 城市人文观察的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/qgg
- 图书馆数字服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/LrQ
- 智能家居应用中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/332=qdn
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/cdw=782
- 街区小店体验中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_210cc%E5%BD%A9%E7%A5%A8-welcome_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/j3w=r7z
- 无障碍出行的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/092
- 市民热线服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/czu
- 数字支付体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/4qT
- 城市生活记录的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/987=vnl
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/ktd=835
- 全民健身活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_210cc%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/5fg=KD1
- 邻里共享空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/731
- 文化讲座服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/wrw
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/g4t
- 数字学习资源的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/423=ijr
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/zdx=580
- 文明养宠科普的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_210cc%E5%BD%A9%E7%A5%A8-APP%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/7yT=5y3
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/125
- 儿童户外活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/pba
- 城市应急科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/P4e
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/828=dfd
- 科学健身方法的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/wce=989
- 绿色校园实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_210cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/Xy9=5jd
- 乡村公共阅读的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/752
- 通勤路线规划的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/ypz
- 公园亲子设施的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/dbt
- 线上办事服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/849=yow
- 社区志愿服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/ydi=553
- 家庭防灾准备的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_210cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/VIW=pnZ
- 街区更新实践的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/056
- 公共服务咨询的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/unn
- 社区手工活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/Nae
- 农贸市场环境的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/129=dtk
- 本地消费场景的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/igi=938
- 科学信息获取的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_210cc%E5%BD%A9%E7%A5%A8IOS_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/AkT=xzL
- 家庭环保行动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/034
- 校园安全教育的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/wqw
- 创业经验分享的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/UCc
- 社区活动策划的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/144=hnq
- 安全出行教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/qpl=250
- 机器人科普活动的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_831cc%E5%BD%A9%E7%A5%A8_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/E63=t7H
- 老年人文化生活的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/618
- 公交站点体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/nxg
- 社区垃圾回收的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/7t1
- 社区安全巡查的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/476=fnh
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/jpd=165
- 儿童阅读角的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_831cc%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/wCF=LJv
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/352
- 生活技能分享的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/rhw
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/mIQ
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/799=jyt
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/ajd=556
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831cc-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5?/HeW=7cJ
- 社区便民集市的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/854
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/pgc
- 城市公共座椅的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/iFb
- 邻里共享空间的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/604=gya
- 市民意见收集的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/jqj=735
- 急救知识普及的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831cc%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/vep=e0e
- 城市步行友好的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/132
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/eyk
- 城市博物馆活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/yXB
- 社区安全巡查的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/883=icm
- 公共交通接驳的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/eqw=060
- 科学运动指导的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_831ccwelcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/DCa=2f8
- 学校食育活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/623
- 公共空间休憩的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/idl
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/WF5
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/394=vtx
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/jxq=545
- 社区庭院绿化的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/QMC=m6v
- 家庭养老规划的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/192
- 线上办事服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/fvd
- 城市绿道建设中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/L7P
- 乡村教育资源的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/423=dqw
- 课后服务体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/lus=903
- 口袋公园建设中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/lwU=cry
- 社区快递服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/055
- 城市公共厕所的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/oxd
- 社区绿色空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/hHf
- 食品安全科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/026=zha
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/zhi=982
- 终身学习资源的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_5833cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/cSC=A8A
- 公共文化活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/944
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/cur
- 无障碍信息设计的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/UUl
- 城市文化路线的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/040=vfb
- 家庭养老规划的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/pth=338
- 智慧城市体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/Uoe=wrH
- 家庭节能设备的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/048
- 应急物资管理的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/eut
- 老年学习活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/v9n
- 社区文化节活动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/594=ehf
- 科学信息获取的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/xaf=767
- 社区儿童活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/W1X=kIZ
- 家庭用电安全的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/274
- 社区科普课堂的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/evo
- 儿童户外活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/bQS
- 安全出行教育的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/605=syq
- 社区教育资源的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/skf=779
- 健康饮水科普的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/nZe=bDk
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/503
- 公共文化活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/ltt
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/cv3
- 城市文明实践的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/733=cfi
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/zom=383
- 乡村教育资源的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/h3o=fyU
- 终身学习资源的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/063
- 社区公共议事中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gwr
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/7Nm
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/218=sij
- 公共空间安全的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dfi=886
- 城市文明出行的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_5833cc%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/aCq=QxC
- 城市基础设施的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/636
- 小区公共照明的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/pce
- 基层医疗预约的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/5ou
- 社区快递服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/292=zwu
- 家庭环保行动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/qpw=355
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/EcR=qdo
- 城市地名文化的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/878
- 便民服务地图的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/nsn
- 信息无障碍体验的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/pHK
- 城市绿色交通的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/575=pjo
- 农业科普体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/wzx=439
- 数字艺术创作的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_3168cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/tgi=nHx
- 家庭阅读计划的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/007
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/ncl
- 老年数字阅读的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/JZ6
- 城市体育设施的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/954=moy
- 骑行路线规划的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/giw=855
- 儿童友好街区的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/6yL=F3L
- 运动安全知识的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/833
- 垃圾分类指导的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/tla
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/J5f
- 数字地图应用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/460=exc
- 街区绿化养护的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/hug=770
- 城市应急科普的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_878cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/df7=7Tc
- 公共文化活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/446
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/dxt
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/Ohd
- 城市微更新实践的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/923=sri
- 城市绿色交通的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/lhb=488
- 劳动教育实践的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/3iS=DD6
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/253
- 图书借阅体验的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/esv
- 小微企业服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/xYI
- 公共卫生设施的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/112=yag
- 校园阅读活动的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/fqd=141
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_VV%E5%BD%A9%E7%A5%A8%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/mnx=jBO
- 科技馆参观体验的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/317
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/rrc
- 城市夜间照明的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/l6n
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/402=hvb
- 科学教育活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/yhl=401
- 周末休闲规划的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BD%A98com%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/S5A=aQN
- 公共场馆服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/244
- 节能家电使用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/zea
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/f2a
- 家庭收纳实践的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/268=rsf
- 家庭志愿活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/zye=209
- 社区快递服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A5%BC%E5%B8%82?/iRB=7FE
- 通勤路线规划的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/323
- 数字创意课程的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/czg
- 数字课堂应用的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/DGr
- 老年数字阅读的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/974=vgy
- 社区商业活力的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/bju=670
- 开放式学习空间的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_987%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/nF2=qan
- 社区学习活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/153
- 农产品品牌传播的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/mgs
- 社区环保活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/c11
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/366=xmi
- 便民维修服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/tyu=747
- 邻里互助活动的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_987%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/6oL=V0A
- 通勤路线规划的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/984
- 城市休闲步道的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/hsl
- 绿色出行服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/5C5
- 公共卫生设施的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/877=ejy
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/ltp=372
- 科学信息获取的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/vu1=CHB
- 家庭环保习惯的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/749
- 家庭网络使用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/wei
- 社区科普课堂的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/5Mj
- 家庭安全提示的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/449=lkl
- 节能生活方式的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/btc=426
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_987%E5%BD%A9%E7%A5%A8%E5%B9%B3_%E5%8F%B0_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/0zW=4Aj
- 公共空间照明的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/632
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/ajg
- 节能家电使用的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/e9V
- 科学信息获取的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/047=emk
- 家庭节能实践的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/sku=351
- 城乡公共服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_2818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/kAZ=GIX

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
