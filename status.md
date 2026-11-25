# 服务器运行状态

**心跳**: 2026-11-25 08:02:02 UTC / 北京时间 2026-11-25 16:02:02

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
| mud-game | online | 4392 | 93MB | 0d 0h 1m |
| mud-web | online | 4283 | 89MB | 0d 0h 1m |
| mud-game-test | online | 1093 | 95MB | 0d 0h 1m |

## 系统

- 内存: 826MB / 3911MB
- 磁盘: 22% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-25）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-11-25 06:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 06:05:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 06:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 06:10:12] Verified release bef985740443c084d29300be52865c25ad92e27f on web and both game services
[2026-11-25 07:25:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 07:25:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-25 07:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 07:30:12] Verified release dfc1f17a82953e459f860050b3281bdfecdec37a on web and both game services
[2026-11-25 08:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-25 08:00:30] Deployment failed at line 60; keep player database and inspect services
```
