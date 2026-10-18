# 服务器运行状态

**心跳**: 2026-10-18 16:02:03 UTC / 北京时间 2026-10-19 00:02:03

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4110 | 92MB | 0d 0h 1m |
| mud-web | online | 4003 | 87MB | 0d 0h 1m |
| mud-game-test | online | 516 | 125MB | 0d 0h 1m |

## 系统

- 内存: 812MB / 3911MB
- 磁盘: 21% 已用（78G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-18）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-18 15:15:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:15:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:20:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:20:30] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:25:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:25:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:30:29] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:35:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:35:29] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:40:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:40:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:45:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:50:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:50:33] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 15:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 15:55:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-18 16:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-18 16:00:29] Deployment failed at line 60; keep player database and inspect services
```
