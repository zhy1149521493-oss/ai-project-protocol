# 候选文档索引

**中文（默认）** | [English](README.en.md)

本包用于审阅 1.3→2.0.0-rc1 的轻量化候选，不是已采用规则或应用项目。只需能读取 Markdown 的 Agent；没有应用启动、构建、AI API 或新增运行依赖。

| 文件 | 作用 |
| --- | --- |
| [CORE](../CORE.md) / [ROUTE](../ROUTE.md) / [STATE](../STATE.md) | 每轮全文规则、完整批准路线与最新实时账，按职责唯一权威 |
| [Skill](../SKILL.md) / [用户版](../PROJECT-EXECUTION-PROTOCOL-USER.md) | 极简读取入口与中文解释，不另立规则 |
| [变化对应](../REFERENCE/CHANGE-MAP.md) | 旧条款到候选、风险及待确认取舍 |
| [记录格式](../REFERENCE/RECORDS.md) | 短工单、正式预算、重大决定及追加模块，按需用 |
| [迁移](../REFERENCE/MIGRATION.md) | 候选批准边界、旧路径兼容、预算与历史继承 |
| [候选决定](../REFERENCE/D-0004-candidate-refactor.md) | 制作原因、方案、代价与未批准采用状态 |
| [验证](VALIDATION.md) / [基线](BASELINE.json) | 纸面检查、完整性与必读量度量；不冒充真实项目效果 |

审阅时直接按 README 提示读取，不安装或发布。采用前先逐项确认差异和迁移记录，不覆盖实例的当前路线/状态。规则先改 CORE，再核对模板/用户解释及链接；普通状态不升规则版本。旧版保持在归档，未来规范变更另行批准。

验证使用已有 Skill 格式校验器和一次性本地文件/链接/哈希检查，不新增依赖或检查框架。工具输出截断须补读；不能用统计结果代替规则审阅。实际检查及限制统一见 VALIDATION，避免重复报告。
