# 量潮数据工程日志

数据工程领域的日志、周报、会议纪要与技术记录。

## 目录结构

```
quanttide-journal-of-data-engineering/
├── default/          # 跨项目的全局日志（数据工程方法论、领域认知）
└── project-record/   # 项目记录：按项目归档的日志 + 档案
    ├── AGENTS.md     # 项目记录撰写规范
    ├── index.md      # 项目档案（通用模板）
    ├── requirement.md # 需求地图（通用模板）
    ├── uspto-entity-matching/  # USPTO 实体匹配项目
    │   ├── 2026-08-19.md   # 项目日志
    │   ├── index.md        # 项目档案
    │   └── requirement.md  # 需求地图
    └── github-activity-panel/ # GitHub 活动面板项目
        ├── 2026-08-19.md   # 项目日志
        ├── index.md        # 项目档案
        └── requirement.md  # 需求地图
```

## project-record 定位

`project-record/` 是「案例式项目」的复盘载体：把一个真实的数据项目做完后，复盘业务经验与问题，沉淀成可开源的数据工程资产。

每个项目一个目录，遵循「日志是事实唯一来源，档案从日志萃取」的链路：

```
journal（日志）→ index.md（项目档案）+ requirement.md（需求地图）
```

- **日志**：记录跑项目过程中的真实过程、踩坑、经验
- **index.md**：从日志萃取出的项目档案（定位/核心目标/数据结构/数据质量/复盘开源/项目上下文）
- **requirement.md**：需求地图（用户画像 + 活动/任务/故事）

档案随迭代更新、反映当前理解，不追求一次写全。
