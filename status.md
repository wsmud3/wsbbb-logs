# 服务器运行状态

**心跳**: 2026-10-23 02:32:02 UTC / 北京时间 2026-10-23 10:32:02

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
| mud-game | online | 4270 | 90MB | 0d 0h 1m |
| mud-web | online | 4161 | 87MB | 0d 0h 1m |
| mud-game-test | online | 848 | 127MB | 0d 0h 1m |

## 系统

- 内存: 1872MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 01:00:01] Dirty checkout; deployment refused
[2026-10-23 01:05:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:05:10] Verified release e799c6f5af558b30da78948003e5153b99faa1a5 on web and both game services
[2026-10-23 01:15:01] Dirty checkout; deployment refused
[2026-10-23 01:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:20:11] Verified release 4e42390de65a85cc4798b28c416f1dbeb2ffb988 on web and both game services
[2026-10-23 01:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:25:12] Verified release e3bc71a51245a8215226369af0ec51edecd2ba32 on web and both game services
[2026-10-23 01:35:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 01:35:10] Verified release 5c7061d85977552cfd6a70f875b819aeb716f471 on web and both game services
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
```
