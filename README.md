# 极客时间 · 许健《技术管理案例课》Skill 知识库

> 基于许健（eBay 基础架构工程研发总监）在极客时间的专栏《技术管理案例课》构建的 WorkBuddy Skill 知识库

## 内容概览

本仓库包含两个 WorkBuddy Skill，覆盖许健8年技术管理实战经验的完整知识体系：

### 1. xujian-tech-management（知识库版）

**定位**：课程知识笔记/方法论查询

- 27章完整内容（覆盖全部24讲 + 开篇词 + 结束语 + 结课测试）
- 核心框架提炼：领导力五层次、向上管理三步法、变革推演法、技术决策三要素等
- 每个模块的结构化知识要点
- 20+个核心管理模型汇总
- 实战案例复盘模板

**触发关键词**：技术管理、团队管理、从技术转管理、管理避坑、向上管理、变革管理、冲突管理、技术决策、招人裁人

### 2. xujian-perspective（人物视角版）

**定位**：许健思维框架模拟/"许健附身"版

基于全部27章内容，通过 [女娲·Skill造人术](https://github.com/alchaincyf/nuwa-skill) 框架的6维度Agent调研，蒸馏出的许健认知操作系统：

- **7大核心心智模型**：信任压力、痛感决策、特殊到普遍、假民主vs真独裁、二线经理下沉两级、向上管理三维、缺陷驱动进化
- **10条决策启发式**
- **表达DNA**：句式特征、高频词汇、类比习惯、情感表达
- **价值观与反模式**
- **内在张力**（5对核心矛盾）
- **20个经典案例索引**
- **6份独立调研文档**（共2897行）

**触发关键词**：许健怎么看、许健会怎么做、用许健的方式分析、技术管理者决策视角

## 两人Skill的区别

| | xujian-tech-management | xujian-perspective |
|--|--|--|
| 定位 | 课程笔记/知识库 | 许健思维框架/角色扮演 |
| 适合问 | "向上管理三步法是什么？" | "用许健的视角分析一下我团队的问题" |
| 输出风格 | 结构化知识点 | 第一人称、案例驱动 |
| 使用方式 | WorkBuddy Skill 直接加载 | WorkBuddy Skill 直接加载 |

## 文件结构

```
geektime-xujian-management/
├── README.md
└── skills/
    ├── xujian-tech-management/
    │   ├── SKILL.md                 ← 582行，完整知识体系
    │   └── references/
    │       ├── 00_开篇词.md
    │       ├── 01_领导力.md
    │       ├── ...（共27个md文件）
    │       └── 结课测试.md
    └── xujian-perspective/
        ├── SKILL.md                 ← 434行，许健思维操作系统
        └── references/
            ├── research/
            │   ├── 01-writings.md
            │   ├── 02-conversations.md
            │   ├── 03-expression-dna.md
            │   ├── 04-external-views.md
            │   ├── 05-decisions.md
            │   └── 06-timeline.md
            └── sources/（27个原文md，与tech-management共享）
```

## 数据来源

- **课程**：极客时间专栏《技术管理案例课》（许健）
- **讲师**：许健，eBay 基础架构工程研发总监，IT行业16年，管理岗8年
- **内容**：全部27篇PDF课件，经OCR清洗后转为Markdown，覆盖从技术骨干到一线经理、二线经理、技术决策者的完整成长路径

## 使用方式

将对应的 skill 目录放入 WorkBuddy 的 `~/.workbuddy/skills/` 目录下即可使用：

```bash
cp -r skills/xujian-tech-management ~/.workbuddy/skills/
# 或
cp -r skills/xujian-perspective ~/.workbuddy/skills/
```

## 许可

本仓库内容仅供个人学习使用，版权归极客邦科技和许健所有。
