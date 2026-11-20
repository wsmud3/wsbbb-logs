# 服务器运行状态

**心跳**: 2026-11-20 12:47:02 UTC / 北京时间 2026-11-20 20:47:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 16m |
| 正式服(200) | running | 0 | 0 | 0d 0h 16m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4358 | 95MB | 0d 0h 16m |
| mud-web | online | 4249 | 87MB | 0d 0h 16m |
| mud-game-test | online | 1040 | 96MB | 0d 0h 16m |

## 系统

- 内存: 829MB / 3911MB
- 磁盘: 23% 已用（76G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-20）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-11-20 12:25:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:25:29] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:30:13] Verified release 24f64d0d0484c9d9499f6d34febce6ad62c46d04 on web and both game services
```
