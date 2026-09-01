# 服务器运行状态

**心跳**: 2026-09-01 19:02:02 UTC / 北京时间 2026-09-02 03:02:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 0m |
| 正式服(200) | running | 0 | 0 | 1d 9h 31m |

## Web 服务

- status: ok | 运行 1d 9h 31m | rss 94MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3789 | 121MB | 0d 0h 0m |
| mud-game | online | 3707 | 98MB | 1d 9h 31m |
| mud-web | online | 3615 | 94MB | 1d 9h 31m |

## 系统

- 内存: 475MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-09-01）

- warn: 0 | error: 0 | fatal: 3

### 今日 fatal（最近 10 条）

```
[2026-09-01 06:15:07] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-09-01 19:00:21] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-09-01 19:00:57] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-09-01 17:25:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:30:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:35:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:40:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:45:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:50:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 17:55:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:00:07] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:05:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:10:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:15:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:20:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:25:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:30:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:35:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:40:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:45:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:50:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 18:55:05] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
[2026-09-01 19:00:06] 前端产物校验通过 28626aa（使用仓库内版本，跳过服务器构建）
```
