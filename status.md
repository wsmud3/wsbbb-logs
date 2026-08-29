# 服务器运行状态

**心跳**: 2026-08-29 20:32:02 UTC / 北京时间 2026-08-30 04:32:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 3h 58m |
| 正式服(200) | running | 2 | 0 | 0d 4h 26m |

## Web 服务

- status: ok | 运行 0d 4h 26m | rss 96MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3779 | 100MB | 0d 3h 58m |
| mud-game | online | 3701 | 96MB | 0d 4h 26m |
| mud-web | online | 3611 | 96MB | 0d 4h 26m |

## 系统

- 内存: 468MB / 3911MB
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
[2026-08-29 18:55:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:00:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:05:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:10:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:15:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:20:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:25:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:30:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:35:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:40:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:45:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:50:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 19:55:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:00:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:05:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:10:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:15:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:20:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:25:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 20:30:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
```
