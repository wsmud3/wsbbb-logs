# 服务器运行状态

**心跳**: 2026-11-20 08:27:02 UTC / 北京时间 2026-11-20 16:27:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 11m |
| 正式服(200) | running | 0 | 0 | 0d 0h 11m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4345 | 94MB | 0d 0h 11m |
| mud-web | online | 4236 | 88MB | 0d 0h 11m |
| mud-game-test | online | 1020 | 96MB | 0d 0h 11m |

## 系统

- 内存: 836MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-20）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-20 06:00:16] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 06:00:38] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 06:05:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 06:05:13] Verified release 686c4f73a9e19b245b33550531994aeef696865d on web and both game services
[2026-11-20 06:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 06:20:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 06:25:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 06:25:13] Verified release ca603f6d3386e80553350fbe189ce0b4b00e4c12 on web and both game services
[2026-11-20 07:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 07:20:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 07:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 07:25:12] Verified release a01dc59267894a5c29d2901bce5e43726ab960c3 on web and both game services
[2026-11-20 07:55:34] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 07:55:57] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 08:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:00:11] Verified release cae4ae98948888cea6271433b8ff81b6fdb06ee5 on web and both game services
[2026-11-20 08:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:10:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 08:15:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:15:14] Verified release 0a6f9cce4cb6aab02007ee679a3925ac167d6f49 on web and both game services
```
