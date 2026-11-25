# 服务器运行状态

**心跳**: 2026-11-25 06:02:03 UTC / 北京时间 2026-11-25 14:02:03

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4387 | 94MB | 0d 0h 1m |
| mud-web | online | 4278 | 88MB | 0d 0h 1m |
| mud-game-test | online | 1085 | 95MB | 0d 0h 1m |

## 系统

- 内存: 834MB / 3911MB
- 磁盘: 22% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-25）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-24 08:00:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 08:00:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-24 08:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 08:05:12] Verified release 262b3c3ce317f2a4ccc42438c69455d3c575d798 on web and both game services
[2026-11-24 20:00:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 20:30:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 22:30:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 22:45:05] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 23:00:05] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 23:30:07] Deployment failed at line 21; keep player database and inspect services
[2026-11-24 23:40:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-25 00:00:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-25 00:30:06] Deployment failed at line 21; keep player database and inspect services
[2026-11-25 01:30:08] Deployment failed at line 21; keep player database and inspect services
[2026-11-25 05:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 05:50:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 05:55:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 05:55:11] Verified release 8814e0accab1c63259e552c58e1b5019065baca2 on web and both game services
[2026-11-25 06:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 06:00:30] Deployment failed at line 60; keep player database and inspect services
```
