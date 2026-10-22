# 服务器运行状态

**心跳**: 2026-10-22 07:52:02 UTC / 北京时间 2026-10-22 15:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 0h 6m |
| 正式服(200) | running | 0 | 0 | 0d 0h 6m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4253 | 92MB | 0d 0h 6m |
| mud-web | online | 4146 | 87MB | 0d 0h 6m |
| mud-game-test | online | 748 | 95MB | 0d 0h 6m |

## 系统

- 内存: 905MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-10-22 07:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:10:11] Verified release 8eedd83a1c64ea37fb3087a8130843f69c020906 on web and both game services
[2026-10-22 07:20:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:20:10] Verified release 55c394fabef87a498fd5248123baaffcfefe2276 on web and both game services
[2026-10-22 07:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:30:11] Verified release 6c099b2c540c13aea1db779752971891821b19f7 on web and both game services
[2026-10-22 07:40:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:40:11] Verified release 87baeed5f9111aa1239c8884b119993dc7d012f6 on web and both game services
[2026-10-22 07:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:45:10] Verified release 4a90287bb7c5adaff905e523ca97b0de1b46feab on web and both game services
```
