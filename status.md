# 服务器运行状态

**心跳**: 2026-11-17 01:27:02 UTC / 北京时间 2026-11-17 09:27:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 12h 6m |
| 正式服(200) | running | 0 | 0 | 0d 12h 6m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4306 | 131MB | 0d 12h 6m |
| mud-web | online | 4197 | 98MB | 0d 12h 6m |
| mud-game-test | online | 960 | 136MB | 0d 12h 6m |

## 系统

- 内存: 945MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-17）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-04 11:50:30] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 12:10:55] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 12:30:47] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 12:55:46] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 13:20:53] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 13:45:32] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 14:05:38] Deployment failed at line 21; keep player database and inspect services
[2026-11-10 13:40:07] Deployment failed at line 21; keep player database and inspect services
[2026-11-13 07:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-13 07:15:13] Verified release f328b12dc1398ee204376c9e0124385b9184ef13 on web and both game services
[2026-11-16 13:00:54] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-16 13:01:15] Deployment failed at line 60; keep player database and inspect services
[2026-11-16 13:05:17] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-16 13:05:39] Deployment failed at line 60; keep player database and inspect services
[2026-11-16 13:10:11] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-16 13:10:33] Deployment failed at line 60; keep player database and inspect services
[2026-11-16 13:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-16 13:15:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-16 13:20:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-16 13:20:12] Verified release fc0ff17a0ccaf4e4e655b99c42010ce01802964b on web and both game services
```
