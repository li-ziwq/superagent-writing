# 文档目录

## Superagent Writing

本项目自己的文档统一放在 `superagent-writing/`，按实际进展增加设计、实现和使用说明。

- [架构讨论稿](superagent-writing/architecture.md)：已确认要求、职责边界、设计建议与待讨论问题；当前尚未批准为实现规格。

## 继承原型参考

以下文档描述从上游继承的开发协作系统，用于理解当前代码，不代表写作系统的目标架构。它们仍被源码、安装说明和测试引用，暂时保留原路径；替换对应模块时同步修订或删除，必要时从 Git 历史查阅旧版。

- [000 Philosophy](000-philosophy.md)
- [001 Domain model](001-domain.md)
- [002 Authorization](002-authorization.md)
- [003 Execution](003-execution.md)
- [004 Prompts](004-prompts.md)
- [005 Panel](005-panel.md)
- [006 Deployment](006-deployment.md)
- [007 Architecture](007-architecture.md)
- [008 Cookbook](008-cookbook.md)
- [原型安装说明](../SETUP.md)

原型的 `prompts/` 和 `skills/` 包含运行时使用的文件，不能当作普通说明文档直接清空。清理时需要一并检查代码引用和相关测试。仓库根目录的许可证与上游版权声明保留。
