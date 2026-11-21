# 服务器运行状态

**心跳**: 2026-11-21 03:52:02 UTC / 北京时间 2026-11-21 11:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 0m |
| 正式服(200) | running | 0 | 0 | 0d 0h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4365 | 92MB | 0d 0h 1m |
| mud-web | online | 4256 | 87MB | 0d 0h 1m |
| mud-game-test | online | 1052 | 123MB | 0d 0h 0m |

## 系统

- 内存: 860MB / 3911MB
- 磁盘: 23% 已用（75G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-21）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-20 12:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:20:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:25:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:30:13] Verified release 24f64d0d0484c9d9499f6d34febce6ad62c46d04 on web and both game services
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
```
