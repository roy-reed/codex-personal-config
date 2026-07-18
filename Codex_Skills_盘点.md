# Codex Skills 盘点

盘点时间：2026-07-19  
范围：Codex 系统技能、用户级技能目录、已安装插件缓存。共发现 44 份 `SKILL.md`、44 个唯一名称。

## 系统技能

| Skill | 功能简介 | 调用方式 |
|---|---|---|
| `imagegen` | 生成或编辑照片、插画、纹理、透明底素材等位图 | 自动/显式 |
| `openai-docs` | 查询 OpenAI/Codex 官方文档、模型与 API 迁移指导 | 自动/显式 |
| `plugin-creator` | 创建、搭建和更新 Codex 插件及 marketplace 配置 | 自动/显式 |
| `review-agent` | 审查代理输出、变更或任务结果并给出结构化质量反馈 | 自动/显式 |
| `skill-creator` | 创建或更新符合规范的 Skill | 自动/显式 |
| `skill-installer` | 从官方目录或 GitHub 安装全局 Skill | 自动/显式 |

## 用户级全局技能

| Skill | 功能简介 | 备注 |
|---|---|---|
| `academic-humanizer` | 学术论文、学位论文、回复信和基金文本去模板化；保持数字、结果与引用不变 | 自动/显式 |
| `arxiv` | 按关键词、作者、分类或 ID 检索 arXiv 论文 | 自动/显式 |
| `grill-me` | 通过连续追问压力测试方案、设计或架构 | 自动/显式 |
| `powerpoint` | 基于 python-pptx 与 YAML 的 PowerPoint 生成和管理 | 自动/显式 |
| `proposal-illustration-generator` | 生成建议书技术路线、机理、对比、验证流程和证据组图；含 265 专用参考 | 自动/显式，建议书插图优先 |
| `research-paper-writing` | ML/CV/NLP 论文各章节写作、结构、论证、图表和投稿前自审 | 自动/显式 |

## 当前启用插件技能

| Skill | 功能简介 | 来源 |
|---|---|---|
| `documents` | 创建、编辑、修订、批注和渲染验证 Word/DOCX | documents 插件 |
| `pdf` | 读取、创建、渲染、检查和验证 PDF | pdf 插件 |
| `Presentations` | 创建或编辑 PowerPoint、Google Slides，并执行视觉 QA | presentations 插件 |
| `Spreadsheets` | 创建、编辑、分析和验证 XLSX/XLS/CSV/TSV | spreadsheets 插件 |
| `excel-live-control` | 控制已连接或打开的实时 Excel 工作簿 | spreadsheets 插件 |
| `template-creator` | 从 Word、PPT 或 Excel 创建可复用个人模板 skill | template-creator 插件 |
| `github` | GitHub 仓库、Issue、PR 的通用分流与概览 | github 插件 |
| `gh-address-comments` | 处理 PR 未解决评审意见和行内评论 | github 插件 |
| `gh-fix-ci` | 排查并修复 GitHub Actions PR 检查失败 | github 插件 |
| `yeet` | 确认范围、提交、推送并创建 GitHub 草稿 PR | github 插件 |
| `gmail` | Gmail 搜索、邮件串总结、行动项提取、回复/转发草拟及整理 | gmail 插件 |
| `gmail-inbox-triage` | 将 Gmail 收件箱分为紧急、需回复、等待、FYI 等 | gmail 插件 |

## 已缓存但当前未启用或需显式选择的插件技能

| Skill | 功能简介 | 状态 |
|---|---|---|
| `artifact-template-analytics-dashboard` | 获客、参与、留存、收入与漏斗 KPI 仪表盘 | 仅显式选择 |
| `artifact-template-business-review` | 业务复盘、KPI、分部结果、优先事项与展望演示 | 仅显式选择 |
| `artifact-template-design-report` | 设计报告、关键发现、影响、建议和附录 | 仅显式选择 |
| `artifact-template-experiment-analysis` | 假设、方法、结果、解释、局限与下一步实验分析 | 仅显式选择 |
| `artifact-template-financial-budget` | 实际、预算、情景预测、差异、现金跑道和部门计划 | 仅显式选择 |
| `artifact-template-investment-committee-memo` | 投委会论点、交易、财务、风险与建议备忘录 | 仅显式选择 |
| `artifact-template-legal-memorandum` | 法律问题、简答、事实、分析和结论备忘录 | 仅显式选择 |
| `artifact-template-market-trends-report` | 市场趋势、证据、影响和建议响应演示 | 仅显式选择 |
| `artifact-template-minimal-letterhead` | 极简信头商务信函 | 仅显式选择 |
| `artifact-template-operating-calendar` | 年度/月度运营里程碑、活动、发布和截止日期 | 仅显式选择 |
| `artifact-template-operating-review` | 周度运营复盘、计分卡、风险、决策和行动项 | 仅显式选择 |
| `artifact-template-project-kickoff` | 项目目标、范围、角色、里程碑、风险与协作模式 | 仅显式选择 |
| `artifact-template-project-tracker` | 工作流、任务、负责人、状态、优先级与甘特计划 | 仅显式选择 |
| `artifact-template-sales-pipeline` | 商机、阶段、负责人、金额、概率、预测和风险 | 仅显式选择 |
| `artifact-template-simple-dark-mode` | 简洁深色演示模板 | 仅显式选择 |
| `artifact-template-simple-light-mode` | 简洁浅色演示模板 | 仅显式选择 |
| `artifact-template-strategy-memorandum` | 战略背景、选项、理由、风险、里程碑与建议 | 仅显式选择 |
| `artifact-template-system-design` | 系统架构、需求、组件、数据流、API 与权衡 | 仅显式选择 |
| `artifact-template-team-alignment` | 团队共识、目标、优先事项、决策和行动项 | 仅显式选择 |
| `artifact-template-three-statement-forecast` | 利润表、资产负债表、现金流三表联动预测 | 仅显式选择 |

## 自动路由说明

- Codex 原生支持隐式调用：当前任务匹配 Skill 的 `description` 时可以自动选择。
- 全局 `~/.codex/AGENTS.md` 增加路由规则后，所有新项目和新任务都会继承“先匹配、选最小充分集合、按依赖顺序组合”的行为。
- 20 个 artifact template skill 明确禁止隐式调用，保留其原设计，避免在未点名模板时擅自套版。
- 插件缓存不等于插件已启用；只有当前可用技能才参与实际自动路由。

