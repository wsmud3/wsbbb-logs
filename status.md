# 服务器运行状态

**心跳**: 2026-11-26 04:37:02 UTC / 北京时间 2026-11-26 12:37:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 19h 1m |
| 正式服(200) | running | 0 | 0 | 0d 19h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4400 | 137MB | 0d 19h 1m |
| mud-web | online | 4291 | 98MB | 0d 19h 1m |
| mud-game-test | online | 1107 | 128MB | 0d 19h 1m |

## 系统

- 内存: 935MB / 3911MB
- 磁盘: 22% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-26）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-25 07:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 07:30:12] Verified release dfc1f17a82953e459f860050b3281bdfecdec37a on web and both game services
[2026-11-25 08:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:00:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 08:05:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:05:13] Verified release 35e6e6f2fd8ab43cbb3a957af8834a2b0ed24d93 on web and both game services
[2026-11-25 08:15:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:15:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 08:20:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:20:34] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 08:25:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:25:13] Verified release 09e654319f9846963f4a86e58d204cc2643ca34e on web and both game services
[2026-11-25 09:20:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 09:20:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 09:25:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 09:25:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 09:30:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 09:30:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 09:35:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 09:35:12] Verified release b365d268a2d09d27fb6dddb56beeb6a117b6d70f on web and both game services
```
