# 服务器运行状态

**心跳**: 2026-08-30 09:42:02 UTC / 北京时间 2026-08-30 17:42:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 4 | 1 | 0d 6h 32m |
| 正式服(200) | running | 3 | 0 | 0d 8h 21m |

## Web 服务

- status: ok | 运行 0d 8h 21m | rss 100MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3784 | 111MB | 0d 6h 32m |
| mud-game | online | 3704 | 95MB | 0d 8h 21m |
| mud-web | online | 3614 | 100MB | 0d 8h 21m |

## 系统

- 内存: 476MB / 3911MB
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
[2026-08-30 08:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:10:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:15:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:20:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:25:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:30:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:35:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:40:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:45:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:50:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 08:55:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:00:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:10:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:15:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:20:11] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:25:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:30:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:35:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 09:40:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
