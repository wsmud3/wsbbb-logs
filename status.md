# 服务器运行状态

**心跳**: 2026-10-23 03:27:02 UTC / 北京时间 2026-10-23 11:27:02

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
| mud-game | online | 4275 | 90MB | 0d 0h 1m |
| mud-web | online | 4166 | 88MB | 0d 0h 1m |
| mud-game-test | online | 872 | 124MB | 0d 0h 0m |

## 系统

- 内存: 1886MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 01:45:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:45:13] Verified release 703d13269a125b405e5ee76134b1b254e84acdea on web and both game services
[2026-10-23 01:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:55:11] Verified release d1453fc1978a10301ff0dd608b264d07c98b3d71 on web and both game services
[2026-10-23 02:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 02:05:10] Verified release 50fa3f1040c468825e5c29f92386fb8012c0c6c4 on web and both game services
[2026-10-23 02:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 02:15:13] Verified release 59ee7e312cc49ec5663bc2e4b3c270c93f87c951 on web and both game services
[2026-10-23 02:30:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 02:30:11] Verified release e208fd6088ee94788f2f1efc9d2b7e0e5e8fb147 on web and both game services
[2026-10-23 02:40:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 02:40:13] Verified release 970ef38c0801e7cef57ac4ce9a6962f69f6b14e8 on web and both game services
[2026-10-23 02:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 02:55:12] Verified release ff73b49f17ad317a6d07b470f17dd6dd137de4e9 on web and both game services
[2026-10-23 03:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:00:11] Verified release 7aa92a0e8f4781bc28dccce295c197d741337883 on web and both game services
[2026-10-23 03:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:20:11] Verified release 5106ad4d26cde4d3188eab946041fed950b88e99 on web and both game services
[2026-10-23 03:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:25:29] Deployment failed at line 60; keep player database and inspect services
```
