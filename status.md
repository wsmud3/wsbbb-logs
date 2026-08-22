# 服务器运行状态

**心跳**: 2026-08-22 08:17:01 UTC / 北京时间 2026-08-22 16:17:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 1h 27m |
| 正式服(200) | running | 0 | 0 | 0d 22h 45m |

## Web 服务

- status: ok | 运行 0d 22h 45m | rss 100MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3739 | 95MB | 0d 1h 27m |
| mud-game | online | 3668 | 99MB | 0d 22h 45m |
| mud-web | online | 3579 | 100MB | 0d 22h 45m |

## 系统

- 内存: 431MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-22）

- warn: 0 | error: 0 | fatal: 10

### 今日 fatal（最近 10 条）

```
[2026-08-22 02:26:34] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:00] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:00] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:35] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:51] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:51] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:30:31] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 03:54:15] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 03:54:56] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 06:49:03] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-22 08:10:06] 前端构建完成 da466dd（www/ 已更新）

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
www/assets/index-S8NWkZZ9.css                           21.02 kB │ gzip:   4.93 kB
www/assets/index-C1Nv-MwH.js                           355.21 kB │ gzip: 100.10 kB

✓ built in 387ms
[2026-08-22 08:15:07] 前端构建完成 da466dd（www/ 已更新）
```
