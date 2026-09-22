# 第三方来源说明

本仓库主体代码基于 `cmliu/edgetunnel`，继续遵循仓库中的 GPL-3.0 许可证。

生产地址池读取自有聚合仓库：

- `254057007-eng/best-cf-ips-personal`
- 公开数据文件：`best-cf-ipv4.txt`

该个人聚合仓库的采集逻辑参考 `LancelotRar/best-cf-ips` 的历史公开实现，但为独立维护版本；具体来源、许可与归属说明以其 `THIRD_PARTY.md` 为准。本项目仅读取其公开输出，自行完成校验、地区筛选、去重、缓存与节点命名。

`LancelotRar/free-subs` 仅用于了解公开订阅的整体使用方式。本项目没有复制其订阅内容、工作流或路由规则。
