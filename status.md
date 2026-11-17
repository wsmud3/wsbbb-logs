# 服务器运行状态

**心跳**: 2026-11-17 09:17:01 UTC / 北京时间 2026-11-17 17:17:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 16m |
| 正式服(200) | running | 0 | 0 | 0d 0h 16m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4319 | 94MB | 0d 0h 16m |
| mud-web | online | 4210 | 88MB | 0d 0h 16m |
| mud-game-test | online | 980 | 98MB | 0d 0h 16m |

## 系统

- 内存: 834MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-17）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-17 03:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 03:25:11] Verified release b7464dba6f8fae9736161167edc6c53c0395fcdb on web and both game services
[2026-11-17 03:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 03:50:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-17 03:55:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 03:55:09] Verified release 818a3301cc8d96fc9ab842b3e82c304cf8cf25e8 on web and both game services
[2026-11-17 04:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-17 04:10:29] Deployment failed at line 60; keep player database and inspect services
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
```
