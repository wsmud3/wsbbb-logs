# 服务器运行状态

**心跳**: 2026-09-17 14:27:01 UTC / 北京时间 2026-09-17 22:27:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 2h 51m |
| 正式服(200) | running | 0 | 0 | 8d 8h 31m |

## Web 服务

- status: ok | 运行 8d 8h 31m | rss 106MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3792 | 100MB | 0d 2h 51m |
| mud-game | online | 3708 | 104MB | 8d 8h 31m |
| mud-web | online | 3616 | 106MB | 8d 8h 31m |

## 系统

- 内存: 491MB / 3911MB
- 磁盘: 14% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-09-17）

- warn: 0 | error: 0 | fatal: 2

### 今日 fatal（最近 10 条）

```
[2026-09-17 11:34:57] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-09-17 11:35:42] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:456:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:240:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-09-17 12:50:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:55:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:00:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:05:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:35:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:40:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:45:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:50:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 13:55:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:00:02] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:05:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 14:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
```
