# 📚 tech-flashcards

A collection of flashcards for developer skills and everyday software usage — practical, hands-on knowledge you actually use.
汇总计算机基础、编程语言与软件应用的实用知识卡片，边用边学，而不是死记硬背理论。

---

## 📁 Directory Structure / 目录结构

```
tech-flashcards/
├── 🧠 01-fundamentals/           # Computer Fundamentals / 计算机基础
│   ├── os/                       # Operating Systems 操作系统
│   ├── network/                  # Computer Networks 计算机网络
│   ├── dsa/                      # Data Structures & Algorithms 数据结构与算法
│   ├── database/                 # Databases 数据库系统
│   ├── computer-organization/    # Computer Organization 计算机组成原理
│   ├── compiler/                 # Compiler Principles 编译原理
│   ├── discrete-math/            # Discrete Mathematics 离散数学
│   ├── software-engineering/     # Software Engineering 软件工程
│   ├── design-patterns/          # Design Patterns 设计模式
│   ├── distributed-systems/      # Distributed Systems 分布式系统
│   └── security/                 # Security & Cryptography 计算机安全 / 密码学
│
├── 💻 02-development/            # Programming Languages / 编程语言
│   ├── python/                   # Python
│   ├── java/                     # Java
│   ├── javascript-typescript/    # JavaScript / TypeScript
│   ├── c/                        # C
│   ├── cpp/                      # C++
│   ├── go/                       # Go
│   ├── rust/                     # Rust
│   ├── kotlin/                   # Kotlin
│   ├── swift/                    # Swift
│   ├── php/                      # PHP
│   ├── ruby/                     # Ruby
│   └── sql/                      # SQL
│
├── 🛠️ 03-productivity/           # Software Applications / 软件应用
│   ├── git/                      # Git
│   ├── docker/                   # Docker
│   ├── vscode/                   # VS Code
│   ├── intellij-idea/            # IntelliJ IDEA
│   ├── vim/                      # Vim
│   ├── postman/                  # Postman
│   ├── kubernetes/                # Kubernetes
│   ├── excel/                    # Excel
│   ├── powerpoint-keynote/       # PowerPoint / Keynote
│   ├── word/                     # Word
│   ├── notion/                   # Notion
│   ├── obsidian/                 # Obsidian
│   ├── anki/                     # Anki
│   ├── trello-jira/              # Trello / Jira
│   └── feishu-dingtalk/          # 飞书 / 钉钉
│
└── README.md
```

---

## 📝 Content / 内容说明

### 🧠 basics/ — Computer Fundamentals / 计算机基础
Core CS knowledge that underlies everyday development work, organized by subject (one folder per subject).
支撑日常开发工作的计算机基础知识，按学科分类（每个学科一个文件夹）。

| Folder 文件夹 | Subject 学科 |
|---|---|
| `os/` | Operating Systems 操作系统 |
| `network/` | Computer Networks 计算机网络 |
| `dsa/` | Data Structures & Algorithms 数据结构与算法 |
| `database/` | Databases 数据库系统 |
| `computer-organization/` | Computer Organization 计算机组成原理 |
| `compiler/` | Compiler Principles 编译原理 |
| `discrete-math/` | Discrete Mathematics 离散数学 |
| `software-engineering/` | Software Engineering 软件工程 |
| `design-patterns/` | Design Patterns 设计模式 |
| `distributed-systems/` | Distributed Systems 分布式系统 |
| `security/` | Security & Cryptography 计算机安全 / 密码学 |

### 💻 lang/ — Programming Languages / 编程语言
Knowledge points for each programming language, organized by language (one folder per language).
面向具体编程语言的知识点，按语言分类（每种语言一个文件夹）。

| Folder 文件夹 | Language 语言 |
|---|---|
| `python/` | Python |
| `java/` | Java |
| `javascript-typescript/` | JavaScript / TypeScript |
| `c/` | C |
| `cpp/` | C++ |
| `go/` | Go |
| `rust/` | Rust |
| `kotlin/` | Kotlin |
| `swift/` | Swift |
| `php/` | PHP |
| `ruby/` | Ruby |
| `sql/` | SQL |

### 🛠️ software/ — Software Applications / 软件应用
Practical tips for commonly used software, organized by software (one folder per tool/app).
常用软件的操作技巧，按软件分类（每个软件一个文件夹）。

| Folder 文件夹 | Software 软件 |
|---|---|
| `git/` | Git |
| `docker/` | Docker |
| `vscode/` | VS Code |
| `intellij-idea/` | IntelliJ IDEA |
| `vim/` | Vim |
| `postman/` | Postman |
| `kubernetes/` | Kubernetes |
| `excel/` | Excel |
| `powerpoint-keynote/` | PowerPoint / Keynote |
| `word/` | Word |
| `notion/` | Notion |
| `obsidian/` | Obsidian |
| `anki/` | Anki |
| `trello-jira/` | Trello / Jira |
| `feishu-dingtalk/` | 飞书 / 钉钉 |

---

## 🃏 Card Format / 卡片格式

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

---

## 📖 How to Use / 使用方式
- 🔍 Browse the markdown files directly to study / 可直接浏览 markdown 文件学习
- 🔁 Import into Anki or other spaced-repetition tools / 也可导入到 Anki 等间隔重复记忆工具中使用

---

## 🤝 Contributing / 维护说明
New cards are welcome — please place them in the folder matching the specific subject / language / software (creating a new folder if needed), and keep the format consistent for long-term accumulation and reuse.
欢迎持续补充新卡片，建议放入对应学科 / 语言 / 软件的文件夹（没有则新建），并保持格式统一，方便长期积累与复用。
