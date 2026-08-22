# 服务器运行状态

**心跳**: 2026-08-22 19:17:02 UTC / 北京时间 2026-08-23 03:17:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 1h 1m |
| 正式服(200) | running | 0 | 0 | 0d 1h 1m |

## Web 服务

- status: ok | 运行 0d 1h 1m | rss 91MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3748 | 90MB | 0d 1h 1m |
| mud-game | online | 3677 | 88MB | 0d 1h 1m |
| mud-web | online | 3587 | 91MB | 0d 1h 1m |

## 系统

- 内存: 431MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-22）

- warn: 0 | error: 1 | fatal: 12

### 今日 error（最近 10 条）

```
[2026-08-22 17:59:04] [ERROR] 未处理的Promise拒绝 | {"reason":"ReferenceError: pars is not defined"}
```

### 今日 fatal（最近 10 条）

```
[2026-08-22 02:27:00] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:35] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:51] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:27:51] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 02:30:31] [FATAL] 未捕获异常 | {"message":"Cannot read properties of undefined (reading 'is_equipment')","stack":"TypeError: Cannot read properties of undefined (reading 'is_equipment')\n    at USER.fb_quick (/home/mud/mud/world/cmd/action/cr.js:115:22)\n    at Timeout._onTimeout (/home/mud/mud/os/base.js:116:13)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 03:54:15] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 03:54:56] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 06:49:03] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 10:43:19] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-22 11:53:24] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-22 19:10:06] 前端构建完成 9cccc3e（www/ 已更新）

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

✓ built in 401ms
[2026-08-22 19:15:06] 前端构建完成 9cccc3e（www/ 已更新）
```
