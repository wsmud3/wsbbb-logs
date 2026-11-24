# 服务器运行状态

**心跳**: 2026-11-24 03:27:02 UTC / 北京时间 2026-11-24 11:27:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 17h 56m |
| 正式服(200) | running | 0 | 0 | 0d 17h 56m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4373 | 136MB | 0d 17h 56m |
| mud-web | online | 4264 | 98MB | 0d 17h 56m |
| mud-game-test | online | 1064 | 137MB | 0d 17h 56m |

## 系统

- 内存: 921MB / 3911MB
- 磁盘: 22% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-24）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-11-23 07:00:10] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-23 07:00:32] Deployment failed at line 60; keep player database and inspect services
[2026-11-23 07:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-23 07:05:12] Verified release fd0bae7fb330164d7654a821db245962ee60d813 on web and both game services
[2026-11-23 08:45:10] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-23 08:45:28] Verified release 76f367b85adec6d22dc87bcb9fc4ba2f47cac9ea on web and both game services
[2026-11-23 09:25:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-23 09:25:28] Deployment failed at line 60; keep player database and inspect services
[2026-11-23 09:30:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-23 09:30:14] Verified release 827c43fba048cda71b90076f3647d95d6e9aaa55 on web and both game services
```
