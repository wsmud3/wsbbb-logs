# 服务器运行状态

**心跳**: 2026-11-20 10:27:02 UTC / 北京时间 2026-11-20 18:27:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 0h 46m |
| 正式服(200) | running | 0 | 0 | 0d 0h 46m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4351 | 96MB | 0d 0h 46m |
| mud-web | online | 4242 | 90MB | 0d 0h 46m |
| mud-game-test | online | 1029 | 99MB | 0d 0h 46m |

## 系统

- 内存: 839MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-20）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-11-20 07:55:34] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 07:55:57] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 08:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:00:11] Verified release cae4ae98948888cea6271433b8ff81b6fdb06ee5 on web and both game services
[2026-11-20 08:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:10:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 08:15:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:15:14] Verified release 0a6f9cce4cb6aab02007ee679a3925ac167d6f49 on web and both game services
[2026-11-20 08:35:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:35:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 08:40:25] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 08:40:30] Verified release 3791ab07e0377fae8a769811a9a4b0891d5d116f on web and both game services
[2026-11-20 09:05:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 09:05:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 09:10:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 09:10:13] Verified release b56845b6c5615a1bee5f849f5572c2de0adff63f on web and both game services
[2026-11-20 09:35:15] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 09:35:37] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 09:40:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 09:40:12] Verified release 76f4555658c946308e7237ddee7cc7a776b21d53 on web and both game services
```
