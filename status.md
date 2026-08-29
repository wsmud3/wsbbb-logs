# 服务器运行状态

**心跳**: 2026-08-29 17:22:01 UTC / 北京时间 2026-08-30 01:22:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 3 | 1 | 0d 0h 48m |
| 正式服(200) | running | 1 | 0 | 0d 1h 16m |

## Web 服务

- status: ok | 运行 0d 1h 16m | rss 94MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3779 | 97MB | 0d 0h 48m |
| mud-game | online | 3701 | 94MB | 0d 1h 16m |
| mud-web | online | 3611 | 94MB | 0d 1h 16m |

## 系统

- 内存: 456MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-29）

- warn: 0 | error: 3 | fatal: 1

### 今日 error（最近 10 条）

```
[2026-08-29 13:15:14] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 14:15:19] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Cannot read properties of undefined (reading 'length')"}
[2026-08-29 17:05:15] [ERROR] 未处理的Promise拒绝 | {"reason":"TypeError: Converting circular structure to JSON\n    --> starting at object with constructor 'Timeout'\n    |     property '_idlePrev' -> object with constructor 'TimersList'\n    --- property '_idleNext' closes the circle"}
```

### 今日 fatal（最近 10 条）

```
[2026-08-29 16:33:28] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-29 15:55:19] 更新至 de62c97（快进合并），健康检查通过，已 pm2 reload
[2026-08-29 16:00:08] 前端产物校验通过 7030f4e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:00:21] 更新至 7030f4e（快进合并），健康检查通过，已 pm2 reload
[2026-08-29 16:05:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:05:20] 更新至 0480c2e（快进合并），健康检查通过，已 pm2 reload
[2026-08-29 16:10:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:15:08] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:20:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:25:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:30:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:35:08] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:40:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:45:08] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:50:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 16:55:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:00:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:05:05] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:10:07] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:15:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
[2026-08-29 17:20:06] 前端产物校验通过 0480c2e（使用仓库内版本，跳过服务器构建）
```
