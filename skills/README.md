# 原创科研 Skills

这里保存从个人实践中提炼的原创或明确注明改编来源的技能。当前尚无可安装技能。

## 发布结构

```text
skills/<skill-name>/
├── SKILL.md          # 元数据、适用任务、步骤与检查
├── references/       # 按需添加详细资料
├── scripts/          # 按需添加辅助脚本
└── assets/           # 按需添加模板和示例材料
```

`SKILL.md` 包含 YAML frontmatter，至少有 `name` 与 `description`；名称与目录一致。详细要求见 [Agent Skills 规范](https://agentskills.io/specification)。可从[技能草稿模板](../templates/skill-draft.md)开始。

| 技能 | 科研任务 | 来源工作流 | 验证环境与日期 | 状态 |
| --- | --- | --- | --- | --- |

发布前须明确：何时调用、需要什么输入、具体交付什么、如何判断完成。用新的任务复验，并记录失败场景。目录结构符合规范不等于已验证所有平台兼容性；兼容性以实际验证记录为准。
