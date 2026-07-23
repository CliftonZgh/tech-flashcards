# tech-flashcards

A collection of flashcards for developer skills and everyday software usage — practical, hands-on knowledge you actually use.

汇总开发技能与日常软件应用的实用知识卡片，边用边学，而不是死记硬背理论。

## Directory Structure / 目录结构

```
tech-flashcards/
├── dev/          # Developer skills flashcards / 开发技能相关卡片（软件工程、编程语言、工具链等）
├── software/     # Everyday software usage flashcards / 日常软件应用相关卡片（常用软件的操作、快捷键、技巧等）
└── README.md
```

## Content / 内容说明

### dev/ — Developer Skills / 开发技能
Knowledge points related to software engineering and development, for example:
面向软件工程与开发相关的知识点，例如：
- Programming language syntax & common APIs / 编程语言语法与常用 API
- Development tools (Git, IDEs, CLI, etc.) / 开发工具使用（Git、IDE、命令行等）
- Engineering practices (debugging, testing, deployment) / 工程实践（调试、测试、部署等）

### software/ — Everyday Software Usage / 日常软件应用
Practical tips for commonly used software in daily work and life, for example:
面向日常工作与生活中常用软件的操作技巧，例如：
- Office software (Office, Excel, PPT, etc.) / 办公软件（Office、Excel、PPT 等）
- Productivity tools (note-taking, task management apps) / 效率工具（笔记、任务管理类应用）
- System & common tool operations / 系统与常用工具操作

## Card Format / 卡片格式

Primarily **cloze (fill-in-the-blank)** format, well-suited for quick review and spaced repetition.
以 **cloze（填空）** 为主，适合快速复习和碎片化记忆，格式示例：

```
The command to view commit history in Git is {{c1::git log}}.
Git 中查看提交历史的命令是 {{c1::git log}}。

The symbol for locking a cell reference in Excel is {{c1::$}}.
Excel 中固定单元格引用的符号是 {{c1::$}}。
```

Multiple blanks can be marked in the same sentence (c1, c2...) to test several points at once:
多个挖空可在同一句中标注多个 cloze（c1、c2...），用于同时测试多个知识点：

```
In {{c1::Vim}}, {{c2::wq}} is used to save and quit.
在 {{c1::Vim}} 中，{{c2::wq}} 用于保存并退出。
```

Tags: `<category tag, e.g. dev/git, software/excel>`
标签：`<分类标签，例如 dev/git、software/excel>`

## How to Use / 使用方式

- Browse the markdown files directly to study / 可直接浏览 markdown 文件学习
- Import into Anki or other spaced-repetition tools / 也可导入到 Anki 等间隔重复记忆工具中使用

## Contributing / 维护说明

New cards are welcome — please place them in the appropriate directory and keep the format consistent for long-term accumulation and reuse.
欢迎持续补充新卡片，建议按类别放入对应目录，并保持格式统一，方便长期积累与复用。
