# 个人 AI 项目操作系统与 HealthyDogPick 项目架构沉淀

> 对话成果整合版｜可复用于后续项目  
> V1.0 · 2026-07-19

## 文档定位

本文件不是聊天逐字稿，而是对当前对话中已经形成的项目架构、管理原则、工作流、文件体系和可复用指令进行去重、校正与结构化沉淀。

## 使用方式

- 作为 Founder Project OS 总纲。
- 作为 HealthyDogPick 项目交接文档。
- 作为未来项目启动、知识库重构和 Agent 设计模板。

## 1. 核心结论与总体架构

### 1.1 两层操作系统

| 层级 | 名称 | 保存内容 | 复用范围 |
|---|---|---|---|
| 通用层 | Founder Project OS | 项目启动、Agent 设计、知识库、工作流、决策、复盘、Token 规则 | 所有未来项目 |
| 项目层 | Project OS / Project HQ | 行业知识、品牌规则、项目战略、执行标准和进度 | 当前项目 |

```text
Founder Project OS Skill
        ↓
Project HQ
        ↓
Specialized Agents
        ↓
Knowledge Base + Projects/Trackers
        ↓
Execution Tools
        ↓
Founder Review
```

### 1.2 人与 AI 的边界

- Founder：方向、资源、风险、最终审批。
- AI HQ：任务拆解、调度、上下文控制和汇总。
- 专业 Agent：研究、分析、草稿、技术方案和优化。
- 执行工具：在明确范围内完成代码、内容或数据任务。

### 1.3 最小团队

1. Project HQ。
2. Strategy / Research。
3. 一个核心 Execution Agent。

只有真实任务量增加后才拆分更多 Agent。

## 2. Founder Project OS

### 2.1 核心原则

- 先判断，后规划，再执行。
- 最小结构起步。
- 长期规则与临时进度分离。
- 一个任务只完成一个连贯成果。
- 事实、证据、经验与推测分开。
- 人工审批是生产闸门。
- 通用方法做 Skill，项目知识留在项目。

### 2.2 生命周期

```text
Idea → Research → Strategy Decision → Planning → Execution → Human Review → Optimization → Scale / Stop
```

### 2.3 决策维度

Market Demand、User Pain、Competition、Monetization、Resource Fit、Execution Difficulty、Long-Term Asset Value、Risk。

默认优先级：可验证小测试 > 重投入；长期资产 > 一次性收益；用户价值 > 激进变现。

### 2.4 Token 规则

- 只加载最少必要文件。
- 一个对话只处理一个交付物。
- Knowledge Base 存长期规则；Tracker 存进度。
- 合并前先审计，不直接删除。
- 浏览器不作为默认执行方式。
- 长对话使用交接摘要后新开。

## 3. 项目知识管理

```text
Project_Name/
├── AGENTS.md
├── Knowledge_Base/
├── Projects/
├── Reports/
├── Archive/
└── README.md
```

- Knowledge Base：长期规则。
- Projects：具体主题和进度。
- Reports：阶段分析。
- Archive：被替代但需要保留的旧版。
- Skill：跨项目工作流。

## 4. Founder Project OS Skill

个人级位置：

```text
$HOME/.agents/skills/founder-project-os/
├── SKILL.md
├── references/
└── assets/
```

触发：新项目、Agent 分工、Knowledge Base/Workflow、架构重构、Token 优化。  
不触发：单篇写作、孤立代码、普通翻译和简单后台操作。

标准输出：Project Diagnosis、Recommended Minimal Structure、Workflow、Files to Create、Founder Actions、AI Actions、Next Approved Action。

## 5. 工具分工

| 工具 | 适合 | 不适合 |
|---|---|---|
| Codex / Website Agent | 分析、方案、任务书、代码与审计 | 浏览器点击默认化、无审核改生产 |
| Cursor | Child Theme、插件、CSS/PHP/JS、模板、Schema | 直接编辑数据库文章、无连接改线上 |
| WordPress 后台 | 内容、图片、分类、菜单、简单设置 | 复杂可维护代码改造 |
| Founder | 审批、上线、权限和方向 | 重复草拟和机械分析 |

## 6. HealthyDogPick 当前基线

- 网站：https://healthydogpick.com/
- 技术：WordPress + GeneratePress + Gutenberg。
- 定位：Dog Health + Product Research。
- 第一阶段：Dog Digestive Health。
- 商业阶段：先积累内容和搜索流量，之后再推进 Affiliate。
- 内容边界：不伪造测试、不冒充兽医、不编造数据，区分事实/证据/经验/推测。
- 团队：HQ、Strategy、SEO、Content、Website Development、Affiliate。
- 资源：内容 70%、SEO/内链 20%、技术 10%。

## 7. Knowledge Base 精简

目标核心文件：

1. 01_Project_Brief.md
2. 02_Brand_Guidelines.md
3. 03_Website_Structure.md
4. 04_Brand_Positioning.md
5. 05_Content_Strategy.md
6. 06_SEO_Strategy.md
7. 07_Affiliate_Strategy.md
8. 08_AI_Operating_System.md
9. 09_Decision_Rules.md
10. 10_Product_Research_Framework.md
11. 11_Content_Template_Library.md
12. 12_Website_Cursor_Workflow.md

Tracker 移入 Projects：Dog Probiotics 与 Joint Supplements。

## 8. Dog Probiotics 内容资产

1. [Probiotics for Dogs: What They Can and Cannot Do](https://healthydogpick.com/probiotics-for-dogs/)
2. [How to Choose a Probiotic for Your Dog](https://healthydogpick.com/how-to-choose-a-dog-probiotic/)
3. [Prebiotics vs. Probiotics vs. Synbiotics for Dogs](https://healthydogpick.com/prebiotics-vs-probiotics-vs-synbiotics-for-dogs/)

下一步：SEO Agent 先做 Cluster SEO Map，包含页面角色、关键词重叠、内容缺口、未来优先级、内链和商业页面规划。

## 9. 标准工作流

### 新项目
Project Brief → Research → Decision → Minimal Team → First Verifiable Asset → Review。

### 内容
SEO Map → Content Brief → Evidence → Draft → Review → Internal Links/Conversion → Publish → QA。

### 网站
Problem → Low-Risk Solution → Cursor Task → Test → Backup/Rollback → Approval → Deploy → Verify。

### Knowledge Base
Inventory → Classify → Merge Plan → New Versions → Migration Map → Approval → Archive/Delete。

## 10. 可直接调用的简版提示词

### 新项目

```text
请使用 Founder Project OS，对该项目做最小可行启动设计。输出 Project Diagnosis、最小团队、最小 Knowledge Base、工作流、风险、Founder/AI 动作和一个下一步。不要一次性创建大量文件。
```

### 架构重构

```text
审计当前 Agent、Knowledge Base、Projects 和工作流。区分长期规则、项目进度、报告和归档；输出目标结构、合并表和迁移表；不要直接删除，等待 Founder 审批。
```

### SEO Cluster

```text
为已发布页面建立 Topic Cluster SEO Map，分析搜索意图、关键词重叠、内容缺口、下一批优先级、内链和商业页面。不要写文章，不要编造搜索量。
```

### Cursor 任务

```text
把网站需求转为 CURSOR_TASK.md，包含问题、最低风险方案、涉及文件、修改步骤、测试、上线和回滚。不要修改 WordPress Core，生产上线前人工审核。
```

## 11. 治理

- 每类信息只保留一个主要事实源。
- 文件状态：Draft / Active / Deprecated / Archived。
- 完成 Skill 与 Knowledge Base 重构后，架构冻结 30 天。

## 12. 当前行动

1. HQ 完成 Knowledge Base 重构预案。
2. 创建 founder-project-os Skill 并测试。
3. SEO Agent 输出 Dog Probiotics Cluster SEO Map。
4. 对三篇内容做上线 QA。
5. 根据 SEO Map 创建下一篇内容资产。

---

完整 Codex 指令、Knowledge Base 重构指令和交接模板见 DOCX 版附录。
