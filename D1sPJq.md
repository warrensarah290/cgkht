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

- 城市绿道建设的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/hvu=101
- 社区艺术活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/eBQ=d6v
- 电子商务服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/588
- 社区文化节活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/vkx
- 全民健身活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/g7q
- 公共服务预约的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/603=pny
- 老年学习活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/cdd=478
- 数字政务体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/Yld=Qm5
- 食品安全科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/838
- 旧物循环利用的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/esp
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/kz1
- 城市水环境观察的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/783=kgt
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/vmw=107
- 绿色建筑理念的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8E%E7%BB%BF%E8%89%B2%E7%89%88_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/tZE=kzc
- 社区停车服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/665
- 科学信息获取的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/fos
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/MC9
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/307=ymu
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/tpu=413
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/GdT=wzX
- 社会体育指导的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/427
- 乡村教育资源的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/bfo
- 户外活动组织的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/2Ik
- 智慧城市体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/704=qcb
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/tzm=374
- 社区商业活力的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7?/HBO=mvj
- 软件开发学习的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/545
- 网络信息辨识的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/pbk
- 乡村公共服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/djf
- 公共设施维护的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/342=qtp
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/etn=281
- 城市展览体验的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%AE%A1%E5%88%92%E4%BB%B6_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/Qk9=vtr
- 生活技能分享的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/586
- 无障碍信息设计的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/tie
- 老旧小区改造的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/OPJ
- 家庭节能实践的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/306=fxo
- 家庭健康科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/pdl=566
- 文明养宠科普中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%97%AD%E5%BD%A9%E7%BD%91xcw_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/HRs=8nN
- 科学教育活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/989
- 生活垃圾回收的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/hee
- 人工智能科普的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/aSE
- 校园节能行动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/479=fjo
- 创业经验分享的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pvg=626
- 读书会组织的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/9Jx=NLC
- 社区家政服务的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/252
- 城市绿色交通的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/giq
- 城市夜间生活的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/w6j
- 个人信息保护的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/008=irn
- 数字阅读服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/rqj=780
- 基层服务创新的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/9bF=0NU
- 城市应急科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/109
- 社区互助网络的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/spe
- 社区邻里服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/S6C
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/906=ori
- 读书会组织的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/iki=324
- 城市绿道建设的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/v9U=oPe
- 城市微更新实践的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/475
- 城市噪声观察的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/sfk
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/L5M
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/214=ijl
- 健康饮食教育的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/cth=528
- 社区防暑服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcomeapp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/Y7d=dWe
- 农贸市场环境的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/466
- 无障碍出行的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/mdp
- 文明养宠科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/fCg
- 公共设施使用的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/278=htf
- 社区共享书架的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/ggf=311
- 居家适老化改造的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/8Bv=RT4
- 本地旅行体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/517
- 全民健身活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/vvb
- 软件开发学习的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/LBo
- 数字阅读服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/726=juf
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/xnj=931
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%97%AD%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/mtd=3SQ
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/167
- 老年人日常照护的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/jiu
- 家庭环保行动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/cCP
- 社区商业活力的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/184=lab
- 网络安全教育的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/rxu=272
- 乡村文化空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/5f0=hsH
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/826
- 老年数字阅读的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/xmh
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/TyM
- 老旧小区改造的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/091=fkv
- 社区邻里服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/tbb=947
- 社区便民集市的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%97%AD%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/kR7=Cs5
- 公共交通接驳的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/691
- 家庭健康管理的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/ces
- 绿色生活实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/qhM
- 社区绿色空间的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/041=ekq
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/cvt=932
- 市民热线服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%97%AD%E5%BD%A9%E7%BD%91welcome2025_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/8cP=TdA
- 乡村文化活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/841
- 社区公共议事的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/iza
- 乡村教育资源的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/kwJ
- 街区道路维护的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/180=pud
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/uzr=664
- 公共交通接驳的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/GEB=67f
- 数据分析入门的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/525
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/tdr
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/H18
- 职业技能学习的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/491=vwg
- 生活技能分享的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/csx=017
- 校园阅读活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%97%AD%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/JSv=Bgy
- 社会体育指导的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/941
- 社区快递服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/mjp
- 社区停车服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/LYY
- 社区便利生活的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/091=doa
- 乡村产业科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/zzl=638
- 社区绿色空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%97%AD%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/SRz=cTp
- 安全出行教育的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/408
- 健康信息获取的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/cyi
- 城市运动公园的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/YMh
- 租房信息服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/013=ayu
- 儿童友好空间的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/ozt=025
- 数字公共文化的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%AD%E5%BD%A9%E7%BD%91~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/bxk=v0n
- 城市应急广播的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/391
- 青年志愿活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/skn
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/OZK
- 小区停车协商的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/307=nqm
- 个人数据管理的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/hmz=218
- 便民维修服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%BD%91%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/8hK=adU
- 城市体育设施的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/014
- 家庭养老规划的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/xsk
- 老年人文化生活的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/3qM
- 基层医疗预约的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/646=nvz
- 城市公共自行车的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/usy=593
- 乡村电商实践的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%97%AD%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/rva=BLL
- 乡村文化活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/493
- 智能手机助老的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/tjb
- 儿童安全出行的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/Z0v
- 城市树木认养的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/442=soc
- 安全出行教育的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/thh=355
- 小区电梯维护的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/nXn=yO7
- 新能源出行的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/830
- 就业技能培训的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/bts
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/R9b
- 乡村文化活动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/313=pww
- 创业经验分享的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/fge=155
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/N7H=BwM
- 图书馆活动策划的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/757
- 城乡公共服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/bmp
- 老年学习活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/bM0
- 家庭园艺实践的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/804=ogq
- 城市骑行环境的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/ojq=505
- 校园节能行动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/hfK=68J
- 人工智能科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/612
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/zhx
- 节假日出行安排的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/b46
- 无障碍信息设计的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/328=bpw
- 农产品品牌传播的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/jpy=483
- 数字档案服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%80%80%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/XRk=T1s
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/963
- 数字素养提升的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/xbv
- 食品配送体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/J4l
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/860=gbm
- 数字学习资源的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/dkg=712
- 乡村文化活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BF%AB3%E7%BD%91_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/O4b=XYg
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/220
- 乡村文化空间的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/blb
- 灵活就业交流的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/m7N
- 职业技能学习的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/526=lrk
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/pog=280
- 便民服务地图的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/Zta=tx2
- 街头绿植养护的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/496
- 文化场馆预约的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/ehu
- 社区艺术活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/4iL
- 农贸市场环境的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/259=jzp
- 社区邻里服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/ecg=134
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/WzI=T4X
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/205
- 家庭防灾准备的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/tjw
- 城市可持续生活的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/yxI
- 公共图书馆服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/237=dhw
- 家庭环保习惯的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/ebg=067
- 文化讲座服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%80%80%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%8E%A2%E5%BA%97?/4VZ=wpv
- 邻里互助活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/742
- 乡村文化活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/xnu
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/i1J
- 数字便民地图的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/513=nvh
- 城乡公共服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/jnb=979
- 社区托育服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/6m8=64L
- 绿色出行服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/854
- 城市空气科普的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/toq
- 社区修缮行动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/Uwe
- 街区小店体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/879=xov
- 城市人文观察的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/aks=896
- 基层医疗预约的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E5%BD%A9%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8F%AF%E9%9D%A0%E5%90%97_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/Njz=8nk
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/437
- 老年人文化生活的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/zpb
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/H4r
- 公共服务预约的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/338=ljk
- 家庭环保行动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/kdh=641
- 公共服务咨询的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/3iW=TqZ
- 青年志愿活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/472
- 科普展览体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/kas
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/gu9
- 网络安全教育的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/148=mzt
- 非遗体验活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/gbf=419
- 就业技能培训的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%80%80%E5%BD%A9%E7%BD%91%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/jxM=UZe
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/664
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/pie
- 公共空间导览的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/5Bu
- 在线教育体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/921=rsw
- 消防知识宣传中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/rur=435
- 城市住房服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E8%80%80%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/nP2=7Mb
- 公共场所导视的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/576
- 街头绿植养护的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/fxj
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/045
- 城市雨天出行的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/567=yyj
- 电动汽车充电中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/gqd=842
- 老年人出行服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E5%BD%A9%E7%BD%91%E6%97%A7%E7%89%88%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/2go=bM6
- 数字资源检索的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/499
- 创业经验分享的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/tae
- 数字课堂应用的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/PcA
- 社区公共餐饮的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/315=fuf
- 社会体育指导的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/wks=031
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%80%80%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/z3Z=0OL
- 社区活动报名的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/796
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/abv
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/fVa
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/673=jvk
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/ihm=548
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/qkD=h8K
- 社区知识分享的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/945
- 城市共享单车的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/pyp
- 非遗体验活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/SjB
- 地方旅游导览的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/487=uyb
- 节气饮食文化的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/zbd=440
- 青少年编程学习的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%9B%88%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/qwH=ZEB
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/202
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/yhi
- 城市体育设施的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/MVl
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/518=pij
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/gbk=319
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%BC%98%E4%B9%90%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/ICR=7AH
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/514
- 线上阅读资源的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/kol
- 环境教育课程的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/rCj
- 邻里互助活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/586=kor
- 公共交通接驳的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ipd=622
- 绿色建筑理念的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BC%98%E4%B9%90%E5%BD%A9-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/1hQ=i2G
- 社区艺术活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/827
- 老年友好服务的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/pmu
- 街区道路维护的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/dIJ
- 灵活就业交流的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/391=xri
- 全民健身活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/pob=523
- 图书馆活动策划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%BC%98%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/7CJ=41t
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/418
- 社区教育资源的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/vbp

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
