# 服务器运行状态

**心跳**: 2026-08-30 17:02:02 UTC / 北京时间 2026-08-31 01:02:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 40m |
| 正式服(200) | running | 2 | 0 | 0d 0h 13m |

## Web 服务

- status: ok | 运行 0d 15h 41m | rss 101MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3785 | 92MB | 0d 0h 40m |
| mud-game | online | 3706 | 91MB | 0d 0h 13m |
| mud-web | online | 3614 | 101MB | 0d 15h 41m |

## 系统

- 内存: 438MB / 3911MB
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
[2026-08-30 15:25:10] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:30:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:35:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:40:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:45:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:50:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 15:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:00:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:10:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:15:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:20:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:25:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:30:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:35:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:40:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:45:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:50:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 16:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 17:00:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
