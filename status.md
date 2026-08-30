# 服务器运行状态

**心跳**: 2026-08-30 14:32:01 UTC / 北京时间 2026-08-30 22:32:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 5 | 0 | 0d 11h 21m |
| 正式服(200) | running | 1 | 0 | 0d 13h 11m |

## Web 服务

- status: ok | 运行 0d 13h 11m | rss 101MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3784 | 107MB | 0d 11h 22m |
| mud-game | online | 3704 | 96MB | 0d 13h 11m |
| mud-web | online | 3614 | 101MB | 0d 13h 11m |

## 系统

- 内存: 475MB / 3911MB
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
[2026-08-30 12:55:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:00:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:05:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:10:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:15:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:20:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:25:05] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:30:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:35:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:40:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:45:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:50:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 13:55:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:00:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:05:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:10:07] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:15:08] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:20:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:25:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
[2026-08-30 14:30:06] 前端产物校验通过 122624d（使用仓库内版本，跳过服务器构建）
```
