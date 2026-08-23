# 服务器运行状态

**心跳**: 2026-08-23 22:37:01 UTC / 北京时间 2026-08-24 06:37:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 0h 25m |
| 正式服(200) | running | 0 | 0 | 0d 12h 16m |

## Web 服务

- status: ok | 运行 0d 12h 16m | rss 99MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3764 | 93MB | 0d 0h 25m |
| mud-game | online | 3688 | 94MB | 0d 12h 16m |
| mud-web | online | 3598 | 99MB | 0d 12h 16m |

## 系统

- 内存: 451MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-23）

- warn: 0 | error: 0 | fatal: 6

### 今日 fatal（最近 10 条）

```
[2026-08-23 11:37:09] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:353:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-23 21:01:16] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:424:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:225:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-23 21:17:10] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-23 21:17:11] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-23 22:10:49] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:353:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-23 22:11:54] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:424:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:225:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-23 22:30:06] 前端构建完成 4015058（www/ 已更新）

> msmud@0.0.1 build
> vite build

vite v8.0.14 building client environment for production...
[2Ktransforming...
../fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular referenced in ../fonts/glyphicons-halflings-regular.svg didn't resolve at build time, it will remain unchanged to be resolved at runtime
✓ 59 modules transformed.
rendering chunks...
computing gzip size...
www/index.html                                           0.42 kB │ gzip:   0.29 kB
www/assets/glyphicons-halflings-regular-BUJKDMgK.eot    20.12 kB
www/assets/glyphicons-halflings-regular-BKjkU69z.woff   23.42 kB
www/assets/glyphicons-halflings-regular-DrwTMapi.ttf    45.40 kB
www/assets/index-CBFwBfKv.css                           21.25 kB │ gzip:   4.96 kB
www/assets/index-WuC3f3_8.js                           355.83 kB │ gzip: 100.36 kB

✓ built in 398ms
[2026-08-23 22:35:07] 前端构建完成 4015058（www/ 已更新）
```
