# 服务器运行状态

**心跳**: 2026-08-30 21:22:02 UTC / 北京时间 2026-08-31 05:22:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 5h 0m |
| 正式服(200) | running | 0 | 0 | 0d 4h 33m |

## Web 服务

- status: ok | 运行 0d 20h 1m | rss 101MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3785 | 96MB | 0d 5h 0m |
| mud-game | online | 3706 | 96MB | 0d 4h 33m |
| mud-web | online | 3614 | 101MB | 0d 20h 1m |

## 系统

- 内存: 458MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-30）

- warn: 0 | error: 0 | fatal: 5

### 今日 fatal（最近 10 条）

```
[2026-08-30 00:32:00] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-30 03:09:55] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-30 16:21:27] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:370:33)\n    at PERFORM.use (/home/mud/mud/world/skill/unarmed/rulaishenzhang.js:80:7)\n    at CHARACTER.use_pfm (/home/mud/mud/world/extends/char/auto_combat.js:85:25)\n    at CHARACTER.check_pfms (/home/mud/mud/world/extends/char/auto_combat.js:175:14)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:44:25)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-30 16:48:30] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-30 16:48:47] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-30 19:45:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 19:50:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 19:55:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:00:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:10:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:15:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:20:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:25:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:30:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:35:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:40:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:45:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:50:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 20:55:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 21:00:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 21:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 21:10:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 21:15:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 21:20:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
