# 服务器运行状态

**心跳**: 2026-11-17 17:52:02 UTC / 北京时间 2026-11-18 01:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 8h 16m |
| 正式服(200) | running | 0 | 0 | 0d 8h 16m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4323 | 135MB | 0d 8h 16m |
| mud-web | online | 4214 | 97MB | 0d 8h 16m |
| mud-game-test | online | 986 | 125MB | 0d 8h 16m |

## 系统

- 内存: 919MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-17）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-17 04:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 04:15:12] Verified release 4758ca4ce23536d414fe2f5fee510fdf6ee37ace on web and both game services
[2026-11-17 07:15:14] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 07:15:34] Verified release a67c4137b1b47d3989f6b7db3c3d7bbe9b43279a on web and both game services
[2026-11-17 07:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 07:45:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-17 07:50:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 07:50:13] Verified release 90e1a5aecb47877226b9e6cf454ce8a3e0410d96 on web and both game services
[2026-11-17 08:55:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 08:55:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-17 09:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 09:00:12] Verified release 4f64fbc08ece704187b18a7faecdffb88eda3f9b on web and both game services
[2026-11-17 09:20:22] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 09:20:44] Deployment failed at line 60; keep player database and inspect services
[2026-11-17 09:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 09:25:10] Verified release 8cffdd961346e053e66f7845705754d9dcf0b9d2 on web and both game services
[2026-11-17 09:30:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 09:30:28] Deployment failed at line 60; keep player database and inspect services
[2026-11-17 09:35:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 09:35:10] Verified release 6d0816e17ae9a527aa90dec28a1c129c970fb575 on web and both game services
```
