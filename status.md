# 服务器运行状态

**心跳**: 2026-08-30 12:07:02 UTC / 北京时间 2026-08-30 20:07:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 4 | 1 | 0d 8h 57m |
| 正式服(200) | running | 1 | 0 | 0d 10h 46m |

## Web 服务

- status: ok | 运行 0d 10h 46m | rss 100MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3784 | 105MB | 0d 8h 57m |
| mud-game | online | 3704 | 95MB | 0d 10h 46m |
| mud-web | online | 3614 | 100MB | 0d 10h 46m |

## 系统

- 内存: 462MB / 3911MB
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
[2026-08-30 10:30:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 10:35:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 10:40:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 10:45:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 10:50:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 10:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:00:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:05:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:10:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:15:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:20:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:25:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:30:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:35:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:40:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:45:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:50:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 11:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 12:00:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 12:05:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
