# 服务器运行状态

**心跳**: 2026-09-17 12:32:02 UTC / 北京时间 2026-09-17 20:32:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 0h 56m |
| 正式服(200) | running | 0 | 0 | 8d 6h 36m |

## Web 服务

- status: ok | 运行 8d 6h 36m | rss 106MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3792 | 97MB | 0d 0h 56m |
| mud-game | online | 3708 | 103MB | 8d 6h 36m |
| mud-web | online | 3616 | 106MB | 8d 6h 36m |

## 系统

- 内存: 474MB / 3911MB
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
[2026-09-17 10:55:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:00:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:05:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:35:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:40:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:45:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:50:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 11:55:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:00:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:05:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-09-17 12:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
```
