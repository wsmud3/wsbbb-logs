# 服务器运行状态

**心跳**: 2026-10-19 00:57:01 UTC / 北京时间 2026-10-19 08:57:01

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
| mud-game | online | 4218 | 111MB | 0d 0h 1m |
| mud-web | online | 4111 | 96MB | 0d 0h 1m |
| mud-game-test | online | 627 | 124MB | 0d 0h 0m |

## 系统

- 内存: 909MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-19）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-19 00:15:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:15:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:20:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:20:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:25:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:25:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:30:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:30:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:35:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:35:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:40:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:40:30] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:45:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:45:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:50:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:50:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:54:47] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:55:08] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 00:55:53] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 00:55:56] Verified release 72736203a0a0540fec2b6fccc997b8dbf8a2a495 on web and both game services
```
