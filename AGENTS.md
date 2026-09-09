# AGENTS.md — jacky-skills

这是 Jacky 的 skill 档案 + 发布层。仓库内容由用户的话驱动：说「加入 / 同步 / 删掉」才会动内容，AI 不自行增删条目。

- **个人 skill**：用户自己写的，平铺在仓库根目录，一个 skill 一个目录，登记在 README.md。
- **推荐的外部 skill**：别人的，只进 COLLECTION.md 做纯索引——源链接和介绍进文档，skill 正文留在原仓库。
- **本地工作层**：`~/.zcode/skills/` 和 `~/.agents/skills/`。日常在本地迭代，收入本仓库即等于归档发布。

所有文档一律中文。提交信息遵循 Conventional Commits（feat / fix / docs 等），描述用中文。

## 条目写法

个人区的小节和推荐区的条目共用一个标准，四个成分：

1. **源链接**：一律指向 skill 的目录、不是单个文档——个人区是本仓库的 `./<name>/`，推荐区是原仓库里该 skill 的目录。目录里除了 SKILL.md 可能还有附属文件。
2. **一段话**：先通读 SKILL.md 再写，以实际内容为准，覆盖「它是什么、解决什么问题」。长度以没见过它的人读完知道该不该用为准——一两句话讲不清就写长，别硬压短。
3. **使用场景**：什么时刻该想起它。
4. **用法**：用户照着说就能触发的那句话。

表格格式和场景分组以 README.md / COLLECTION.md 现状为准，增改保持一致。

## 「我要加入这个 skill」+ URL → 推荐区

1. 抓取并通读 URL 指向的 SKILL.md（只到 SKILL.md 或 README，整仓不翻）。
2. 按「条目写法」写出条目。
3. 归入 COLLECTION.md 目录里最合适的场景分组；现有分组都不合适就新建一个，目录表同步更新。
4. git commit，提交信息带 skill 名。

用户说「这是我自己写的」或「我要改造它」时，改走下面的个人区流程；拿不准归属就问一句。默认：URL 指向别人的仓库 → 推荐区。

## 「同步我本地的 skill」→ 个人区

1. 确定范围：用户点名的 skill；没点名就列出两个本地根目录里所有未收录的 skill 让用户挑。
2. 从 `~/.zcode/skills/<name>/` 或 `~/.agents/skills/<name>/` 整目录拷入仓库根目录，附属文件（references/、scripts/、agents/ 等）一起。
3. 按「条目写法」更新 README.md：目录表加一行，并新增小节。
4. git commit，提交信息带 skill 名。

仓库里已有同名 skill 时：diff 两边内容，把差异摆给用户选，绝不自动覆盖。

## 「写个新 skill」→ 个人区

1. 在根目录建 `<name>/SKILL.md` 骨架（frontmatter：name、description），内容配合 skill-creator 完成。
2. 按「条目写法」更新 README.md：目录表加一行，并新增小节。
3. git commit，提交信息带 skill 名。
