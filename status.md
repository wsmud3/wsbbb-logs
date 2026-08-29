# 服务器运行状态

**心跳**: 2026-08-29 22:42:01 UTC / 北京时间 2026-08-30 06:42:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 0h 56m |
| 正式服(200) | running | 0 | 0 | 0d 0h 56m |

## Web 服务

- status: ok | 运行 0d 0h 56m | rss 94MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3781 | 95MB | 0d 0h 56m |
| mud-game | online | 3703 | 89MB | 0d 0h 56m |
| mud-web | online | 3613 | 94MB | 0d 0h 56m |

## 系统

- 内存: 426MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-29）

- warn: 0 | error: 7 | fatal: 1

### 今日 error（最近 10 条）

```
[2026-08-29 13:15:14] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 14:15:19] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 17:05:15] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 17:33:40] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 18:05:20] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 19:05:25] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 20:05:30] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
```

### 今日 fatal（最近 10 条）

```
[2026-08-29 16:33:28] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-29 21:15:06] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:15:18] 更新至 b95707a（快进合并），健康检查通过，已 pm2 reload
[2026-08-29 21:20:06] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:25:06] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:30:06] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:35:06] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:40:05] 前端产物校验通过 b95707a（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:45:06] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:45:18] 更新至 71f6d0b（快进合并），健康检查通过，已 pm2 reload
[2026-08-29 21:50:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 21:55:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:00:06] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:05:06] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:10:06] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:15:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:20:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:25:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:30:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:35:05] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
[2026-08-29 22:40:06] 前端产物校验通过 71f6d0b（使用仓库内版本，跳过服务器构建）
```
