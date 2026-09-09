# COLLECTION — 推荐的 Skills

平时在用、觉得好的别人的 skill。这里只做索引，不搬源码：想用哪个，点源链接去原仓库装。收录标准：我自己在真实使用，并且愿意推荐。

## 目录

### 学习

| 名字 | 一句话 | 源链接 |
| --- | --- | --- |
| [teach](#teach) | 把当前目录变成一间教室，按课程设计长期攻克一个主题 | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/productivity/teach) |
| [eli5](#eli5) | 像对 5 岁小孩讲解一样科普一个概念：大图、少字、一眼看懂 | [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community/tree/main/eli5/skills/eli5) |

### 调研

| 名字 | 一句话 | 源链接 |
| --- | --- | --- |
| [hv-analysis](#hv-analysis) | 横纵分析法深度研究：纵向追时间线、横向追竞品，交汇出判断，产出万字 PDF 报告 | [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills/tree/main/hv-analysis) |

### 决策

| 名字 | 一句话 | 源链接 |
| --- | --- | --- |
| [grilling](#grilling) | 动手前无情拷问你的计划，一轮一轮问下去，直到没有想当然的分支 | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) |

### 元技能

| 名字 | 一句话 | 源链接 |
| --- | --- | --- |
| [find-skills](#find-skills) | 从开源 skill 生态里搜索、把关、安装现成的 skill | [vercel-labs/skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) |
| [handoff](#handoff) | 把当前会话压缩成交接文档，让下一个全新 agent 无缝接手 | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/productivity/handoff) |

---

## teach

**源链接**：https://github.com/mattpocock/skills/tree/main/skills/productivity/teach

把当前工作区当成一间「教学工作室」来长期跟学：`MISSION.md` 记录你到底为什么学这个，所有教学围绕它展开；每节课产出一节短小、排版精致、可交互的 HTML 课程存进 `lessons/`，速查表沉淀到 `reference/`，`learning-records/` 记录你已经学到哪，用来计算你的「最近发展区」、决定下一课教什么。课程设计刻意区分「当下流利」和「长期记住」，用检索练习、间隔、交错来对抗学完就忘。**适合**认真攻克一个新领域、打算学一阵子而不是问一次就走的场景。**用法**：在学习目录里说「教我 X」或 `/teach X`。

## eli5

**源链接**：https://github.com/anthropics/claude-plugins-community/tree/main/eli5/skills/eli5

一句话需求的极简科普：解释主题时默认读者对它一无所知，产出一个大图少字的 HTML 图解页面。不追求深度，追求第一眼看懂「这东西是干嘛的」，先在脑子里建立起正确的心智图像，之后再深入不迟。**适合**面对一个完全陌生的概念、又不想立刻啃文档的时刻。**用法**：`/eli5 <主题>`，或直接说「给我讲讲 X，当我是小白」。

## hv-analysis

**源链接**：https://github.com/KKKKhazix/khazix-skills/tree/main/hv-analysis

数字生命卡兹克提出的横纵分析法：纵向沿时间轴还原研究对象从诞生到现在的完整故事（起源、关键节点、每个决策背后的逻辑），横向与同赛道竞品做当前切面的对比（格局、真实用户口碑、生态位），最后把两条轴交汇出综合判断，并推演最可能、最危险、最乐观三个未来剧本。全程必须联网多路并行搜索、一手来源优先，搜不到的诚实标注而不是编造，最终产出一份 1–3 万字、自带封面和排版的 PDF 深度报告。**适合**认真研究一个产品、公司、概念或人物，想要「能从头读到尾的报告」而不是搜索摘要拼盘。**用法**：说「帮我用横纵分析法研究 X」或「深度研究 / 竞品分析 X」。

## grilling

**源链接**：https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling

在你动手之前，让 AI 无情拷问你的计划：把要做的事情展开成一棵决策树，每一轮把当前所有「前置条件已经齐了」的问题一次性抛出来——每个都带编号和它的推荐答案，你答完它再根据答案推出下一轮，直到整棵树没有一处靠默认假设糊弄过去。核心价值是逼你把「想当然」变成「明确决定」，免得 AI 拿错误的默认值盖了半天楼。**适合**启动项目、做方案、下决定之前。**用法**：说「拷问我」或「grill me on this plan」。

## find-skills

**源链接**：https://github.com/vercel-labs/skills/tree/main/skills/find-skills

开源 skill 生态的入口：当你在想「有没有现成的 skill 能做 X」时，它先查 skills.sh 排行榜看有没有经过大量验证的方案，再用 `npx skills find` 搜索，并替你把关质量（装机量、来源信誉、GitHub stars），最后给出安装命令、你说装就装。**适合**「我想干 X，但不想自己造轮子」的时刻，也是给本仓库 COLLECTION 补货的挖掘机。**用法**：直接问「有没有做 X 的 skill」。

## handoff

**源链接**：https://github.com/mattpocock/skills/tree/main/skills/productivity/handoff

会话临结束前，把整个对话压缩成一份交接文档，存到系统临时目录（不污染工作区），让下一个全新 agent 能无缝接手：specs、commits、diff 里已有的内容不重复写、引用路径即可，明确列出下一个 agent 应该加载哪些 skill，并主动脱敏 API key 等敏感信息。**适合**长任务跨会话、或者换工具、换模型接力的时刻。**用法**：说「做个 handoff」，可附一句下一个会话的用途，文档会朝那个方向写。
