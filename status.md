# 服务器运行状态

**心跳**: 2026-10-23 01:17:02 UTC / 北京时间 2026-10-23 09:17:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 1m |
| 正式服(200) | running | 1 | 1 | 0d 0h 11m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4262 | 91MB | 0d 0h 11m |
| mud-web | online | 4153 | 87MB | 0d 0h 11m |
| mud-game-test | online | 808 | 125MB | 0d 0h 2m |

## 系统

- 内存: 1807MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-22 23:40:01] Dirty checkout; deployment refused
[2026-10-22 23:45:01] Dirty checkout; deployment refused
[2026-10-22 23:50:01] Dirty checkout; deployment refused
[2026-10-22 23:55:01] Dirty checkout; deployment refused
[2026-10-23 00:00:02] Dirty checkout; deployment refused
[2026-10-23 00:05:01] Dirty checkout; deployment refused
[2026-10-23 00:10:01] Dirty checkout; deployment refused
[2026-10-23 00:15:01] Dirty checkout; deployment refused
[2026-10-23 00:20:01] Dirty checkout; deployment refused
[2026-10-23 00:25:01] Dirty checkout; deployment refused
[2026-10-23 00:30:01] Dirty checkout; deployment refused
[2026-10-23 00:35:01] Dirty checkout; deployment refused
[2026-10-23 00:40:01] Dirty checkout; deployment refused
[2026-10-23 00:45:01] Dirty checkout; deployment refused
[2026-10-23 00:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 00:50:11] Verified release ae62c6a2147c475e1bb3cf6bacba1ee8c8f37515 on web and both game services
[2026-10-23 01:00:01] Dirty checkout; deployment refused
[2026-10-23 01:05:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:05:10] Verified release e799c6f5af558b30da78948003e5153b99faa1a5 on web and both game services
[2026-10-23 01:15:01] Dirty checkout; deployment refused
```
