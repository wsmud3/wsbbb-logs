# 服务器运行状态

**心跳**: 2026-10-15 00:32:01 UTC / 北京时间 2026-10-15 08:32:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 5m |
| 正式服(200) | running | 0 | 0 | 0d 0h 5m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3761 | 90MB | 0d 0h 5m |
| mud-web | online | 3655 | 86MB | 0d 0h 5m |
| mud-game-test | online | 111 | 93MB | 0d 0h 5m |

## 系统

- 内存: 453MB / 3911MB
- 磁盘: 19% 已用（79G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-15）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-14 22:55:01] Dirty checkout; deployment refused
[2026-10-14 23:00:01] Dirty checkout; deployment refused
[2026-10-14 23:05:01] Dirty checkout; deployment refused
[2026-10-14 23:10:01] Dirty checkout; deployment refused
[2026-10-14 23:15:01] Dirty checkout; deployment refused
[2026-10-14 23:20:01] Dirty checkout; deployment refused
[2026-10-14 23:25:01] Dirty checkout; deployment refused
[2026-10-14 23:30:01] Dirty checkout; deployment refused
[2026-10-14 23:35:01] Dirty checkout; deployment refused
[2026-10-14 23:40:01] Dirty checkout; deployment refused
[2026-10-14 23:45:01] Dirty checkout; deployment refused
[2026-10-14 23:50:01] Dirty checkout; deployment refused
[2026-10-14 23:55:01] Dirty checkout; deployment refused
[2026-10-15 00:00:01] Dirty checkout; deployment refused
[2026-10-15 00:05:01] Dirty checkout; deployment refused
[2026-10-15 00:10:01] Dirty checkout; deployment refused
[2026-10-15 00:15:01] Dirty checkout; deployment refused
[2026-10-15 00:20:01] Dirty checkout; deployment refused
[2026-10-15 00:25:05] Deployment failed at line 18; keep player database and inspect services
[2026-10-15 00:26:45] Verified release c752086caaeb026a80d2239b312d9e4336cb6116 on web and both game services
```
