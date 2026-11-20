# 服务器运行状态

**心跳**: 2026-11-20 12:22:02 UTC / 北京时间 2026-11-20 20:22:02

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
| mud-game | online | 4356 | 91MB | 0d 0h 1m |
| mud-web | online | 4247 | 87MB | 0d 0h 1m |
| mud-game-test | online | 1037 | 123MB | 0d 0h 0m |

## 系统

- 内存: 868MB / 3911MB
- 磁盘: 23% 已用（75G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-20）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-11-20 11:00:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 11:00:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 11:05:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 11:05:12] Verified release a44711e38db8d60cda243b38dd607cc5e7d40f8e on web and both game services
[2026-11-20 11:55:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 11:55:30] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:00:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:00:12] Verified release 5447b26a7a1ce7d35dbe994e7933b5b963714196 on web and both game services
[2026-11-20 12:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:20:30] Deployment failed at line 60; keep player database and inspect services
```
