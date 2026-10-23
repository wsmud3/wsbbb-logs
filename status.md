# 服务器运行状态

**心跳**: 2026-10-23 07:32:02 UTC / 北京时间 2026-10-23 15:32:02

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
| mud-game | online | 4290 | 91MB | 0d 0h 1m |
| mud-web | online | 4181 | 87MB | 0d 0h 1m |
| mud-game-test | online | 922 | 125MB | 0d 0h 1m |

## 系统

- 内存: 969MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 04:15:13] Verified release 3ee1432c7a3d26be8c83e4e4c26008093762f104 on web and both game services
[2026-10-23 04:55:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 04:55:33] Deployment failed at line 60; keep player database and inspect services
[2026-10-23 05:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 05:00:11] Verified release 57d6f126c09ca1b3494232e72e12d545b4a755ad on web and both game services
[2026-10-23 05:40:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 05:40:11] Verified release 5f5ee156c90f036381b2fa35643b14abd5e5dc62 on web and both game services
[2026-10-23 06:05:01] Dirty checkout; deployment refused
[2026-10-23 06:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 06:10:13] Verified release b12d8afe591345389b5c9dc909b99ba248b18507 on web and both game services
[2026-10-23 06:35:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 06:35:15] Verified release 04d3b101e3050714215fa1713d9a101cba4c8d64 on web and both game services
[2026-10-23 06:40:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 06:40:11] Verified release f78e8555ba9da0d0482f4fb661faadce5d13354f on web and both game services
[2026-10-23 07:05:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:05:16] Verified release be7bc0b1b343a177d10777631a64fc886c7b718d on web and both game services
[2026-10-23 07:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:20:12] Verified release 615b6ced06ca53b51bceb9b103203d22db4dc85a on web and both game services
[2026-10-23 07:30:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:30:11] Verified release 85bb0e38d6e095bf82786a7dc69a4207713bebc2 on web and both game services
```
