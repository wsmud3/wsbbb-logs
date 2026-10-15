# 服务器运行状态

**心跳**: 2026-10-15 06:02:02 UTC / 北京时间 2026-10-15 14:02:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 3m |
| 正式服(200) | running | 0 | 0 | 0d 0h 3m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3773 | 90MB | 0d 0h 3m |
| mud-web | online | 3667 | 85MB | 0d 0h 3m |
| mud-game-test | online | 144 | 92MB | 0d 0h 3m |

## 系统

- 内存: 440MB / 3911MB
- 磁盘: 19% 已用（79G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-15）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-10-15 05:45:12] Deployment failed at line 34; keep player database and inspect services
[2026-10-15 05:45:46] Verified release b6a9024f1424ca49509b9730a1272eae051e1b76 on web and both game services
[2026-10-15 05:55:05] Deployment failed at line 18; keep player database and inspect services
[2026-10-15 05:56:47] Dirty checkout; deployment refused
[2026-10-15 05:58:11] Verified release f6772cb7531132e14695a8aba8a50a9b18d4ee2c on web and both game services
```
