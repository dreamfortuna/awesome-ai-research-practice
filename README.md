# Awesome AI Research Practice

**AI + 科研实践手册**：记录 AI 辅助科研的真实经验，整理值得试用的工具与 Agent Skills，把经过验证的方法沉淀为可复用工作流和原创技能。

维护者：[dreamfortuna](https://github.com/dreamfortuna)。中文为主，目录与技能名称使用英文。

## Contents

- [从哪里开始](#从哪里开始)
- [按科研任务查找](#按科研任务查找)
- [资源与验证状态](#资源与验证状态)
- [从经验到 Skill](#从经验到-skill)
- [仓库结构](#仓库结构)
- [接下来做什么](#接下来做什么)

## 从哪里开始

| 你的目的 | 入口 |
| --- | --- |
| 找工具、外部技能和参考项目 | [资源索引](resources/README.md) |
| 看个人使用经验、问题与复盘 | [实践笔记](notes/README.md) |
| 按步骤完成一类科研任务 | [科研工作流](workflows/README.md) |
| 使用本仓库的原创技能 | [原创 Skills](skills/README.md) |
| 添加一条自己的记录 | [记录模板](templates/README.md) |
| 了解命名、目录与维护方式 | [仓库策划](docs/repository-plan.md) |

## 按科研任务查找

统一按科研过程分类；新增内容时在对应索引中标记分类，条目增多后再拆分子目录。

| 分类标识 | 科研任务 | 典型产出 |
| --- | --- | --- |
| `research-ideation` | 选题、问题定义与研究设计 | 问题陈述、假设、实验方案 |
| `literature-review` | 文献检索、精读与证据核对 | 检索记录、证据表、阅读笔记 |
| `experiments-and-code` | 科研编程、实验与复现 | 实验记录、代码、复现报告 |
| `data-and-statistics` | 数据处理与统计分析 | 分析脚本、统计结果、数据字典 |
| `figures-and-presentations` | 科研绘图与汇报 | 图表、演示文稿、图注 |
| `academic-writing` | 论文写作、修改与审稿回复 | 草稿、修改记录、回复信 |
| `research-management` | 知识管理与科研协作 | 文献库、项目记录、归档方案 |

## 资源与验证状态

**链接存在、文档看起来合适，与实际好用是不同的证据。** 所有外部条目明确标注状态：

| 状态 | 含义 |
| --- | --- |
| 待验证 | 已发现且与任务相关，尚未实际执行 |
| 试用中 | 已开始试用，证据或适用范围仍不完整 |
| 已验证 | 有可检查的使用记录，明确验证日期、版本和环境 |
| 暂不推荐 | 试用发现问题，保留理由与替代方案 |
| 归档 | 历史记录；维护状态或适用环境已变化 |

初始资源全部为**待验证**，详见[外部 Skills 候选](resources/agent-skills.md)。本仓库尚无已验证的个人案例或可安装的原创技能。

## 从经验到 Skill

```text
发现资源 → 实际试用 → 记录经验与失败 → 整理工作流 → 提炼原创 Skill → 用新任务复验
```

一次试用先写笔记；能够重复执行的方法再整理为工作流；输入、步骤、交付和检查方法稳定后再创建 Skill。每个原创技能都应链接其来源笔记、工作流和验证记录。

外部技能以来源链接和评估记录为主；如果改编或引入文件，记录上游版本、许可证和改动。原创技能统一放在 `skills/<skill-name>/SKILL.md`，结构参考 [Agent Skills 规范](https://agentskills.io/specification)。

## 仓库结构

```text
awesome-ai-research-practice/
├── README.md                 # 首页与分类导航
├── CONTRIBUTING.md           # 收录与贡献约定
├── resources/                # 外部资源链接及试用评价
│   ├── README.md
│   └── agent-skills.md
├── notes/README.md           # 个人实践笔记索引
├── workflows/README.md       # 可复用科研流程索引
├── skills/README.md          # 原创技能索引
├── templates/               # 笔记、资源卡、工作流、技能模板
├── docs/repository-plan.md   # 仓库策划与维护方式
└── .github/ISSUE_TEMPLATE/   # 资源或经验建议入口
```

## 接下来做什么

1. 选择一个近期真实任务，完成第一条实践笔记。
2. 试用一个相关外部 Skill，记录输入、结果、版本、成本与问题。
3. 从重复出现的任务中提炼第一份工作流，再决定是否沉淀为原创 Skill。

欢迎通过 [Issue](https://github.com/dreamfortuna/awesome-ai-research-practice/issues) 提供资源或实践线索，提交要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。许可证方案见[仓库策划](docs/repository-plan.md#许可证建议)；当前尚未选定开放许可证。
