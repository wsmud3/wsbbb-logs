# 服务器运行状态

**心跳**: 2026-11-21 07:57:02 UTC / 北京时间 2026-11-21 15:57:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 3h 51m |
| 正式服(200) | running | 0 | 0 | 0d 3h 51m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4368 | 125MB | 0d 3h 51m |
| mud-web | online | 4259 | 94MB | 0d 3h 51m |
| mud-game-test | online | 1056 | 141MB | 0d 3h 51m |

## 系统

- 内存: 927MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-21）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-20 12:50:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:50:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:55:12] Verified release 33851c5cfed2d32e4f2a1582085d4e578cc4fb75 on web and both game services
[2026-11-21 03:10:10] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:10:32] Deployment failed at line 60; keep player database and inspect services
[2026-11-21 03:15:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:15:11] Verified release 3268aa8e1e16f66784a07a089269ef9977a1d568 on web and both game services
[2026-11-21 03:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:20:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-21 03:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:25:12] Verified release 4a58959cb4c1b831f8f3201ee8b63763afb8f181 on web and both game services
[2026-11-21 03:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:50:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-21 03:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 03:55:11] Verified release 864eb962e95574085183fd863d84c467391dfaae on web and both game services
[2026-11-21 04:00:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 04:00:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-21 04:05:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-21 04:05:16] Verified release f62b96328b0131907d489736ce5a2e02f6794edb on web and both game services
```
