# 服务器运行状态

**心跳**: 2026-11-24 16:42:02 UTC / 北京时间 2026-11-25 00:42:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 8h 36m |
| 正式服(200) | running | 0 | 0 | 0d 8h 36m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4384 | 132MB | 0d 8h 36m |
| mud-web | online | 4275 | 96MB | 0d 8h 36m |
| mud-game-test | online | 1081 | 139MB | 0d 8h 36m |

## 系统

- 内存: 923MB / 3911MB
- 磁盘: 22% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-24）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-24 04:10:10] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 04:10:15] Verified release b8ff285441a2b26f468f3d4a0323a4742bf21f33 on web and both game services
[2026-11-24 05:40:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 05:40:35] Deployment failed at line 60; keep player database and inspect services
[2026-11-24 05:45:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 05:45:13] Verified release ea66a5ecf25333d8e78cd5cd8a092d0c91217718 on web and both game services
[2026-11-24 06:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 06:10:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-24 06:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 06:15:13] Verified release 5e5d0a9ff957e76502b17551bdc0bb75655e44fd on web and both game services
[2026-11-24 06:50:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 06:50:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-24 06:55:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 06:55:11] Verified release 0f9d5a5af4a32a60e97c95d9ea32496a80610cf7 on web and both game services
[2026-11-24 07:45:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 07:45:29] Verified release 64e2394af868c9e73db87c7be5b989b91e2657bb on web and both game services
[2026-11-24 08:00:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 08:00:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-24 08:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-24 08:05:12] Verified release 262b3c3ce317f2a4ccc42438c69455d3c575d798 on web and both game services
```
