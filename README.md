<div align="center">

# 🧰 Jacky Skills

我日常在用的 AI Agent Skills

</div>

仓库分两块：

- **个人 Skills**：自己写和维护的，平铺在根目录。
- **推荐的 Skills**：使用过程觉得不错的 skills，详细见：[COLLECTION.md](./COLLECTION.md)。

## 个人 Skills

| 名字 | 痛点 | 一句话 |
| --- | --- | --- |
| [rename-session](./rename-session/) | AI 会话太多太乱，回头找不到开过的会话 | 按「MMDD \| 类型 \| 主题」格式给 AI 会话起名 |

### rename-session

给会话列表里的 AI 会话起一个规范名字，格式固定为 `MMDD | 类型 | 主题`，例如 `0909 | 研究 | 会话命名类型体系调研`。日期取会话创建当天；类型从一个 21 项的闭集清单里选，判据是会话的主要产出（功能、修复、调试、评审、研究、写作……），两者都沾时看最终交付了什么；主题用 10–20 字写清「对什么、做什么」，细节优先于简短。它只产出名称文本，绝不改项目名，遇到归类不了的就保留原名并提议扩充类型清单。

**使用场景**：当你和 AI 的会话多到列表没法扫，想靠扫一眼名字就找回「那天调那个 bug 的会话」时。

**怎么用**：对话里直接说「给这个会话起个名」。

## 推荐的 Skills

详细见 [COLLECTION.md](./COLLECTION.md)。

| 名字 | 痛点 | 一句话 |
| --- | --- | --- |
| [teach](https://github.com/mattpocock/skills/tree/main/skills/productivity/teach) | 自学新领域没体系，学完就忘 | 把当前目录变成一间教室，按课程设计长期攻克一个主题 |
| [eli5](https://github.com/anthropics/claude-plugins-community/tree/main/eli5/skills/eli5) | 面对陌生概念，文档啃不动 | 像对 5 岁小孩讲解一样科普：大图、少字、一眼看懂 |
| [hv-analysis](https://github.com/KKKKhazix/khazix-skills/tree/main/hv-analysis) | 深度研究对象时，搜索摘要拼盘不够用 | 横纵分析法：纵向追时间线、横向追竞品，产出万字 PDF 报告 |
| [grilling](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) | 计划没想透就开工，AI 拿错误的默认值瞎做 | 动手前无情拷问你的计划，直到没有想当然的分支 |
| [find-skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) | 想干一件事，不知道有没有现成的 skill | 从开源 skill 生态里搜索、把关、安装现成的 skill |
| [handoff](https://github.com/mattpocock/skills/tree/main/skills/productivity/handoff) | 长任务跨会话接力，上下文丢了 | 把当前会话压缩成交接文档，让下一个 agent 无缝接手 |

