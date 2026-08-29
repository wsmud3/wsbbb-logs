# 服务器运行状态

**心跳**: 2026-08-29 18:37:01 UTC / 北京时间 2026-08-30 02:37:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 2h 3m |
| 正式服(200) | running | 1 | 0 | 0d 2h 31m |

## Web 服务

- status: ok | 运行 0d 2h 31m | rss 94MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3779 | 97MB | 0d 2h 3m |
| mud-game | online | 3701 | 95MB | 0d 2h 31m |
| mud-web | online | 3611 | 94MB | 0d 2h 31m |

## 系统

- 内存: 445MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-29）

- warn: 0 | error: 5 | fatal: 1

### 今日 error（最近 10 条）

```
[2026-08-29 13:15:14] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 14:15:19] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 17:05:15] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 17:33:40] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
[2026-08-29 18:05:20] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
```

### 今日 fatal（最近 10 条）

```
[2026-08-29 16:33:28] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-29 17:00:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:05:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:10:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:15:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:20:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:25:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:30:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:35:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:40:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:45:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:50:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:55:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:00:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:05:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:10:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:15:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:20:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:25:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:30:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 18:35:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
```
