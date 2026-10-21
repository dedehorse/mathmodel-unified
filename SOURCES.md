# 组成来源与公开边界

`mathmodel-unified` 是根据作者本机已有工作流重新编写的统一入口，不是将原 skills、附件或模板原样合并。下表说明设计思路来自哪里；这些原 skill 无须安装，统一 skill 可以单独使用。

| 本项目部分 | 参考的本地 skill | 吸收的思路 |
| --- | --- | --- |
| 任务路由、计划和阶段衔接 | `1start-mathmodel` | 完整任务才建立计划，阶段间传递可检查的产物 |
| 题意与模型 | `2analysis-modeling`、`math-reasoning` | 子问题、数据、假设、变量、目标、约束与可实现性 |
| 代码与结果 | `3coding-visual`、`pyomo`、`cuopt-numerical-optimization-formulation` | 可复现求解、基线、约束与误差检查；后两者是可选专业工具 |
| 图表 | `4drawio`、`mathmodel-figure-templates`、`sci-palette` | 区分数据图与方法图，保留图表来源与可编辑文件 |
| 论文 | `5writing`、`typst-author`、`pdf` | 依据结果写作，选择适用模板与引擎，检查 PDF |
| 技术验收 | `6verity`、`bzd-paper-format-checker`、`bzd-review-paper` | 数值、格式、匿名、可复现性和成品质量检查 |
| 赛事适配 | `cumcm-live-workflow`、`cumcm-review-insights`、`_references` | 完整竞赛的规则门禁与评阅视角；具体规则必须回到当届官方文件 |
| 经验与环境 | `mathmodel-school-materials`、`doctor`、`global-biblio-base` | 题型与验证经验、环境检查、文献核验；均为可选参考或工具 |

**没有随仓库发布**：学校培训原文、历年评阅材料与评分细则、赛事官方 PDF/Word、第三方论文模板、图表模板脚本、竞赛题面与数据、个人论文、账号/本机路径。这些材料的授权和适用年份各不相同；需要时由使用者从合法来源另行提供或核验。本仓库不宣称代表赛事组委会、学校或上表所列第三方 skill 的作者。

本目录中的 `SKILL.md`、说明文档及元数据是为此次整合新写的文本，按本目录的 MIT 许可证开放。该许可证不覆盖上段未发布的材料，也不自动覆盖仓库的其他目录。
