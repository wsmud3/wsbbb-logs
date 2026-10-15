# 服务器运行状态

**心跳**: 2026-10-15 05:42:02 UTC / 北京时间 2026-10-15 13:42:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 0m |
| 正式服(200) | running | 0 | 0 | 0d 0h 0m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3767 | 111MB | 0d 0h 0m |
| mud-web | online | 3661 | 96MB | 0d 0h 0m |
| mud-game-test | online | 127 | 116MB | 0d 0h 0m |

## 系统

- 内存: 502MB / 3911MB
- 磁盘: 19% 已用（79G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-15）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-15 04:10:01] Dirty checkout; deployment refused
[2026-10-15 04:15:01] Dirty checkout; deployment refused
[2026-10-15 04:20:01] Dirty checkout; deployment refused
[2026-10-15 04:25:01] Dirty checkout; deployment refused
[2026-10-15 04:30:01] Dirty checkout; deployment refused
[2026-10-15 04:35:01] Dirty checkout; deployment refused
[2026-10-15 04:40:01] Dirty checkout; deployment refused
[2026-10-15 04:45:01] Dirty checkout; deployment refused
[2026-10-15 04:50:01] Dirty checkout; deployment refused
[2026-10-15 04:55:01] Dirty checkout; deployment refused
[2026-10-15 05:00:01] Dirty checkout; deployment refused
[2026-10-15 05:05:01] Dirty checkout; deployment refused
[2026-10-15 05:10:01] Dirty checkout; deployment refused
[2026-10-15 05:15:01] Dirty checkout; deployment refused
[2026-10-15 05:20:01] Dirty checkout; deployment refused
[2026-10-15 05:25:01] Dirty checkout; deployment refused
[2026-10-15 05:30:01] Dirty checkout; deployment refused
[2026-10-15 05:35:01] Dirty checkout; deployment refused
[2026-10-15 05:40:05] Deployment failed at line 18; keep player database and inspect services
[2026-10-15 05:42:01] Verified release 3d447af90abff5422c178d8766da32d425bb3077 on web and both game services
```
