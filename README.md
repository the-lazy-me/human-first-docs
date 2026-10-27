# human-first-docs · 为人写文档

面向 AI 编程 Agent 的工程文档与注释写作 Skill。让项目方案、架构设计、实施计划与交接材料直接呈现读者需要的**问题、目标、决策、结构和行动**。

重点约束：过度防御性否定、自我辩论、无用比喻、术语与代码堆砌、执行日志污染正文，以及将临时任务混入长期文档。修改时保留必要事实与设计约束；默认宁缺毋滥。

## 使用

将本仓库的 `SKILL.md` 放到 AI Agent 的技能目录，例如：

```text
~/.agents/skills/human-first-docs/SKILL.md
```

然后在创建、修改或审查项目文档时使用 `human-first-docs`，或直接要求 Agent 按此 Skill 执行。

所有规则见 [SKILL.md](SKILL.md)。
