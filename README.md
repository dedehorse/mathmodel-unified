# MathModel Unified

一个可独立安装的 Codex 数学建模 skill。它把读题与建模、可复现求解、数据图与方法图、论文写作、终审交付放在同一入口；咨询或单阶段任务只处理所需范围。

## 安装

从 [dedehorse/mathmodel-unified](https://github.com/dedehorse/mathmodel-unified) 下载仓库，将仓库目录命名为 `mathmodel-unified` 并放到 `~/.codex/skills/`，重启或刷新 Codex 的 skill 列表。也可将目录放到支持 `SKILL.md` 的其他 agent 的 skills 目录。

无需安装本地原有的六个分阶段 skill；Typst、LaTeX、DrawIO 或求解器只在相应任务需要时安装。

## 使用示例

- “用 `mathmodel-unified` 分析这道数模题的子问题和关键假设。”
- “按完整流程完成这道竞赛题，保留可复现代码和终审报告。”
- “只检查现有论文的数值一致性和当届格式要求。”

skill 会先读取你提供的题面、附件和适用规则。它不会把旧赛事的页数、AI 规定或提交时间套到新赛事上。

## 组成与来源

六阶段主流程来自本地 `1start-mathmodel` 至 `6verity` 的经验整理；赛事门禁参考 `cumcm-live-workflow`，评阅与格式检查参考 `cumcm-review-insights`、`bzd-paper-format-checker` 等。完整映射、未发布材料和许可边界见 [SOURCES.md](SOURCES.md)。本仓库提供重新编写的工作流文本，不附带学校资料、官方文件、第三方模板或个人参赛材料。

## 许可

本仓库原创文本采用 [MIT License](LICENSE)。赛事规则和第三方材料各归其权利人所有。
