# 服务器运行状态

**心跳**: 2026-10-23 04:42:02 UTC / 北京时间 2026-10-23 12:42:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 26m |
| 正式服(200) | running | 0 | 0 | 0d 0h 26m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4281 | 93MB | 0d 0h 26m |
| mud-web | online | 4172 | 90MB | 0d 0h 26m |
| mud-game-test | online | 893 | 95MB | 0d 0h 26m |

## 系统

- 内存: 1854MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 02:55:12] Verified release ff73b49f17ad317a6d07b470f17dd6dd137de4e9 on web and both game services
[2026-10-23 03:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:00:11] Verified release 7aa92a0e8f4781bc28dccce295c197d741337883 on web and both game services
[2026-10-23 03:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:20:11] Verified release 5106ad4d26cde4d3188eab946041fed950b88e99 on web and both game services
[2026-10-23 03:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:25:29] Deployment failed at line 60; keep player database and inspect services
[2026-10-23 03:30:01] Dirty checkout; deployment refused
[2026-10-23 03:35:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:35:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-23 03:40:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:40:11] Verified release 94a786c8799ab13a6b5e4331ab0563c0572c9c36 on web and both game services
[2026-10-23 03:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:50:11] Verified release c89bae32bffdf8419f0206c09e804a49c1e61d94 on web and both game services
[2026-10-23 03:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 03:55:11] Verified release 3eafa93f0b750a47cee444aaf1ba9088f1a2f291 on web and both game services
[2026-10-23 04:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 04:00:13] Verified release af5138081c08ab7d76bbe204605a2716f71f867e on web and both game services
[2026-10-23 04:15:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 04:15:13] Verified release 3ee1432c7a3d26be8c83e4e4c26008093762f104 on web and both game services
```
