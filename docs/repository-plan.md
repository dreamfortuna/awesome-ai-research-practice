# 仓库策划

## 名称与定位

确定名称：`awesome-ai-research-practice`。

中文标题：**AI + 科研实践手册**。

简介：**AI-assisted research in practice: personal field notes, curated resources, reproducible workflows, and original agent skills.**

核心是“用 AI 做科研”的实践积累，同时容纳文献、实验、数据、绘图、写作和知识管理。外部资源为实践提供输入，个人经验是持续积累的主体，原创技能是方法稳定后的产物。

备选名称及取舍：

| 名称 | 优势 | 取舍 |
| --- | --- | --- |
| `awesome-ai-research-practice` | 兼顾精选入口与实践积累，范围可扩展 | 名称稍长 |
| `ai-research-playbook` | 强调个人方法与工作流，表达简洁 | 不直接体现 Awesome 资源策展 |
| `awesome-research-skills` | 技能主题突出，容易理解为技能目录 | 难以涵盖尚未提炼成技能的经验 |

## 目录职责

| 目录 | 保存什么 | 进入条件 |
| --- | --- | --- |
| `resources/` | 外部来源、候选技能与评价 | 与科研任务相关，有可访问来源 |
| `notes/` | 真实操作、结果、问题与复盘 | 完成或尝试过具体任务 |
| `workflows/` | 可以重复执行的方法 | 步骤、输入、输出与检查可说明 |
| `skills/` | 可调用的原创或明确标注改编的技能 | 来源明确，并有任务验证记录 |
| `templates/` | 统一记录格式 | 对维护有直接帮助 |
| `docs/` | 仓库定位与维护约定 | 需要长期保存的仓库说明 |

首页是入口与精选，不放全部长文。外部资源按科研任务分类，笔记按日期命名，技能按能力命名。同一份事实只维护一次，其他位置使用链接。

## 内容如何流转

1. 发现外部资源，记入候选并注明“待验证”。
2. 在真实任务中试用，保存环境、版本、输入、输出与检查记录。
3. 根据证据更新状态；失败经验也保存。
4. 重复出现的有效步骤提炼为工作流，保留来源链接。
5. 方法稳定后再写 Skill，用新的任务复验，并注明已验证的平台范围。

不要给没有使用过的资源写“亲测好用”；不要用 Star 数替代适用性判断；不要把验证单个技能扩展为验证整个集合。

## 初期维护方式

采用 Markdown 与 Git 历史，直接维护索引。资源少时使用单个分类文件，有足够内容后再拆分；不预先建立大量空目录。

初始建议标签：`ai`、`research`、`research-workflows`、`agent-skills`、`awesome-list`、`awesome`。这些是建议，实际仓库设置另行核验。

每次更新按内容检查来源、相对链接、状态与证据一致性。内容规模增加后再评估链接检查、静态文档站或结构化目录，初期不引入自动抓取和重复维护的数据层。

## 许可证建议

原创经验文档可考虑 CC BY 4.0；原创技能或脚本可考虑 MIT，并通过独立许可证文件明确各自范围。第三方内容遵循上游许可证。

初始版本尚未选择或授予开放许可证，待维护者确定后添加完整许可文本。许可证方案参考 [GitHub 的仓库许可说明](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)和 [Creative Commons 的 CC BY 4.0 说明](https://creativecommons.org/licenses/by/4.0/)。

## 参考仓库与借鉴点

- [sindresorhus/awesome](https://github.com/sindresorhus/awesome)：学习明确范围、分类导航、精选理由和贡献约定。
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)：学习外部技能集合的分类与来源索引。
- [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs)：学习科研与工程技能的组织方式，其主题偏 AI/ML 研究。
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)：考察跨科学任务的技能组织方式。
- [Agent Skills 规范](https://agentskills.io/specification)：采用 `SKILL.md` 及可选资源目录的技能结构。

本仓库借鉴导航与组织方式，不以进入 Awesome 总目录为当前目标，也不宣称初始候选均已验证。
