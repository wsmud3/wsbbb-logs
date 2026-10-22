# 服务器运行状态

**心跳**: 2026-10-22 07:07:02 UTC / 北京时间 2026-10-22 15:07:02

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
| mud-game | online | 4248 | 91MB | 0d 0h 1m |
| mud-web | online | 4141 | 87MB | 0d 0h 1m |
| mud-game-test | online | 739 | 125MB | 0d 0h 0m |

## 系统

- 内存: 925MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-22 05:35:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:35:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-22 05:40:13] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:40:17] Verified release 8ed514400234ef0df2dbe25c2971df1934f8a811 on web and both game services
[2026-10-22 06:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:00:11] Verified release 3a1004d8cb69c380dd5e6bcf36ad80a012f4b5cb on web and both game services
[2026-10-22 06:05:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:05:10] Verified release aa018a1c69c804310128512d01aa20f5cb852c34 on web and both game services
[2026-10-22 06:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:20:11] Verified release bdc790f7e95263d9e895a57b2f81029c03135aad on web and both game services
[2026-10-22 06:30:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:30:11] Verified release 16c9d53b41ac32576c3d83703cb8d1afe82583dc on web and both game services
[2026-10-22 06:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:45:11] Verified release eca84e823628aebbc75433151c64ec5bbb6ebe0f on web and both game services
[2026-10-22 06:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:50:11] Verified release 5624b5e3c59d212b9b64e33c4a994b4b00825f03 on web and both game services
[2026-10-22 07:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:00:11] Verified release 2df9b4cfdcec172b352d186afa43627576c945c0 on web and both game services
[2026-10-22 07:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:05:27] Deployment failed at line 60; keep player database and inspect services
```
