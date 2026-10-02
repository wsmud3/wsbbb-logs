# 服务器运行状态

**心跳**: 2026-10-02 22:47:02 UTC / 北京时间 2026-10-03 06:47:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 12m |
| 正式服(200) | running | 0 | 0 | 23d 16h 51m |

## Web 服务

- status: ok | 运行 23d 16h 51m | rss 110MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3795 | 96MB | 0d 0h 12m |
| mud-game | online | 3708 | 103MB | 23d 16h 51m |
| mud-web | online | 3616 | 110MB | 23d 16h 51m |

## 系统

- 内存: 515MB / 3911MB
- 磁盘: 17% 已用（81G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-02）

- warn: 0 | error: 0 | fatal: 4

### 今日 fatal（最近 10 条）

```
[2026-10-02 22:26:19] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-02 22:26:20] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-02 22:26:42] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-02 22:34:25] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:385:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-02 21:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:25:02] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:35:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:40:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:45:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:50:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 21:55:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:00:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:05:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:35:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:40:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-10-02 22:45:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
```
