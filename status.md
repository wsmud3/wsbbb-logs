# 服务器运行状态

**心跳**: 2026-11-20 17:52:02 UTC / 北京时间 2026-11-21 01:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 4h 45m |
| 正式服(200) | running | 0 | 0 | 0d 4h 56m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4360 | 137MB | 0d 4h 56m |
| mud-web | online | 4251 | 94MB | 0d 4h 56m |
| mud-game-test | online | 1044 | 153MB | 0d 4h 45m |

## 系统

- 内存: 941MB / 3911MB
- 磁盘: 23% 已用（75G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-20）

- warn: 0 | error: 0 | fatal: 1

### 今日 fatal（最近 10 条）

```
[2026-11-20 13:06:02] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'indexOf')","stack":"TypeError: Cannot read properties of undefined (reading 'indexOf')\n    at Timeout._onTimeout (/home/mud/mud-test/world/skill/force/taijishengong2.js:81:57)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
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
[2026-11-20 12:50:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:50:31] Deployment failed at line 60; keep player database and inspect services
[2026-11-20 12:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-20 12:55:12] Verified release 33851c5cfed2d32e4f2a1582085d4e578cc4fb75 on web and both game services
```
