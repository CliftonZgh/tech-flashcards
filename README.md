# tech-flashcards
A collection of flashcards for developer skills and everyday software usage — practical, hands-on knowledge you actually use.
汇总计算机基础、编程语言与软件应用的实用知识卡片，边用边学，而不是死记硬背理论。

## Directory Structure / 目录结构
```
tech-flashcards/
├── basics/
│   ├── os/                  # 操作系统
│   ├── network/             # 计算机网络
│   ├── dsa/                 # 数据结构与算法
│   ├── database/            # 数据库系统
│   ├── computer-organization/  # 计算机组成原理
│   ├── compiler/            # 编译原理
│   ├── discrete-math/       # 离散数学
│   ├── software-engineering/   # 软件工程
│   ├── design-patterns/     # 设计模式
│   ├── distributed-systems/ # 分布式系统
│   └── security/            # 计算机安全 / 密码学
│
├── lang/
│   ├── python/
│   ├── java/
│   ├── javascript-typescript/
│   ├── c/
│   ├── cpp/
│   ├── go/
│   ├── rust/
│   ├── kotlin/
│   ├── swift/
│   ├── php/
│   ├── ruby/
│   └── sql/
│
├── software/
│   ├── git/
│   ├── docker/
│   ├── vscode/
│   ├── intellij-idea/
│   ├── vim/
│   ├── postman/
│   ├── kubernetes/
│   ├── excel/
│   ├── powerpoint-keynote/
│   ├── word/
│   ├── notion/
│   ├── obsidian/
│   ├── anki/
│   ├── trello-jira/
│   └── feishu-dingtalk/
│
└── README.md
```

## Content / 内容说明

### basics/ — Computer Fundamentals / 计算机基础
Core CS knowledge that underlies everyday development work, for example:
支撑日常开发工作的计算机基础知识，例如：
- Operating systems (processes, memory, file systems) / 操作系统（进程、内存、文件系统等）
- Networking (protocols, HTTP, DNS) / 计算机网络（协议、HTTP、DNS 等）
- Data structures & algorithms / 数据结构与算法
- Databases (SQL basics, indexing, transactions) / 数据库（SQL 基础、索引、事务等）

### lang/ — Programming Languages / 编程语言
Knowledge points related to specific programming languages, for example:
面向具体编程语言的知识点，例如：
- Syntax & common APIs / 语法与常用 API
- Language-specific features & idioms / 语言特性与惯用写法
- Standard library usage / 标准库使用

### software/ — Software Applications / 软件应用
Practical tips for commonly used software in development and daily work, for example:
面向开发与日常工作中常用软件的操作技巧，例如：
- Development tools (Git, IDEs, CLI, etc.) / 开发工具（Git、IDE、命令行等）
- Office software (Office, Excel, PPT, etc.) / 办公软件（Office、Excel、PPT 等）
- Productivity tools (note-taking, task management apps) / 效率工具（笔记、任务管理类应用）

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

Tags: `<category tag, e.g. basics/network, lang/python, software/excel>`
标签：`<分类标签，例如 basics/network、lang/python、software/excel>`

## How to Use / 使用方式
- Browse the markdown files directly to study / 可直接浏览 markdown 文件学习
- Import into Anki or other spaced-repetition tools / 也可导入到 Anki 等间隔重复记忆工具中使用

## Contributing / 维护说明
New cards are welcome — please place them in the appropriate directory (`basics/`, `lang/`, or `software/`) and keep the format consistent for long-term accumulation and reuse.
欢迎持续补充新卡片，建议按类别放入 `basics/`、`lang/`、`software/` 对应目录，并保持格式统一，方便长期积累与复用。
