# 服务器运行状态

**心跳**: 2026-08-30 07:27:02 UTC / 北京时间 2026-08-30 15:27:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 4h 17m |
| 正式服(200) | running | 1 | 0 | 0d 6h 6m |

## Web 服务

- status: ok | 运行 0d 6h 6m | rss 98MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3784 | 106MB | 0d 4h 17m |
| mud-game | online | 3704 | 94MB | 0d 6h 6m |
| mud-web | online | 3614 | 98MB | 0d 6h 6m |

## 系统

- 内存: 468MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-30）

- warn: 0 | error: 0 | fatal: 2

### 今日 fatal（最近 10 条）

```
[2026-08-30 00:32:00] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-30 03:09:55] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-30 05:50:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 05:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:00:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:05:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:10:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:15:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:20:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:25:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:30:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:35:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:40:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:45:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:50:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 06:55:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:00:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:05:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:10:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:15:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:20:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 07:25:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
