# 服务器运行状态

**心跳**: 2026-11-19 21:37:02 UTC / 北京时间 2026-11-20 05:37:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 11h 56m |
| 正式服(200) | running | 0 | 0 | 0d 11h 56m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4333 | 130MB | 0d 11h 56m |
| mud-web | online | 4224 | 96MB | 0d 11h 56m |
| mud-game-test | online | 1002 | 134MB | 0d 11h 56m |

## 系统

- 内存: 922MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-19）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-19 04:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 04:10:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-19 04:15:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 04:15:14] Verified release 9f787d15afa1fd8258859c709f2def5fe5aad324 on web and both game services
[2026-11-19 08:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 08:15:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-19 08:20:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 08:20:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-19 08:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 08:25:12] Verified release febe7465d7e7c08bfaa451866a72378c1c5fd016 on web and both game services
[2026-11-19 08:55:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 08:55:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-19 09:00:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 09:00:13] Verified release 5feab57f2ee11d3971e90523ce0e3608cacf224a on web and both game services
[2026-11-19 09:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 09:15:28] Verified release d5db32e94c0af3cceb4676b18a0f866577d8e140 on web and both game services
[2026-11-19 09:35:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 09:35:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-19 09:40:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-19 09:40:12] Verified release c3d2d0b24a6465c3a3af6c868fc0b93adf550c65 on web and both game services
```
