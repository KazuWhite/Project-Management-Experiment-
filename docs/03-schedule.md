# 03 简化进度计划

| 编号 | 活动名称 | 工期 | 前置关系 | 责任人 | 对应交付物 |
|---|---|---|---|---|---|
| A1 | 仓库初始化与分支创建 | 1天 | 无 | luochengruixin | Git仓库与目录结构 |
| A2 | 编写项目章程与README | 1天 | A1 | lairuilin | 01-project-charter.md, README.md |
| A3 | 完成三级WBS分解 | 1天 | A1 | luochengruixin | 02-wbs.md |
| A4 | 制定进度计划 | 1天 | A3 | luochengruixin | 03-schedule.md |
| A5 | 编写配置管理方案 | 1天 | A1 | lizhuoqing | 04-config-plan.md |
| A6 | 制造与解决合并冲突 | 1天 | A4, A5 | luochengruixin, lizhuoqing | conflict.md |
| A7 | 完成总结报告 | 1天 | A2, A5, A6 | 全组 | 05-summary-report.md |
| A8 | 合并至main分支并验收 | 1天 | A7 | lizhuoqing | 最终提交至main |

## 说明
本进度计划依据WBS关键交付物提取，各项活动均明确对应成果物；前置关系基于“先建库、再分工、再集成、最后验收”的逻辑串联，关键路径为 A1→A5→A6→A7→A8。