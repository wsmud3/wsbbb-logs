# 服务器运行状态

**心跳**: 2026-08-21 12:47:01 UTC / 北京时间 2026-08-21 20:47:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 1h 25m |
| 正式服(200) | running | 0 | 0 | 0d 3h 15m |

## Web 服务

- status: ok | 运行 0d 3h 15m | rss 95MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3729 | 97MB | 0d 1h 25m |
| mud-game | online | 3668 | 93MB | 0d 3h 15m |
| mud-web | online | 3579 | 95MB | 0d 3h 15m |

## 系统

- 内存: 427MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-21）

- warn: 0 | error: 0 | fatal: 6

### 今日 fatal（最近 10 条）

```
[2026-08-21 04:58:41] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:418:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:219:25)\n    at BASE.on_parry_over (/home/mud/mud/world/skill/parry/yixinghunyuan.js:54:12)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:351:40)\n    at PERFORM.use (/home/mud/mud/world/skill/unarmed/rulaishenzhang.js:55:8)\n    at CHARACTER.use_pfm (/home/mud/mud/world/extends/char/auto_combat.js:85:25)\n    at CHARACTER.check_pfms (/home/mud/mud/world/extends/char/auto_combat.js:175:14)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:44:25)\n    at listOnTimeout (node:internal/timers:605:17)"}
[2026-08-21 06:33:39] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-21 06:33:59] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-21 08:46:34] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_force_over (/home/mud/mud/world/skill/force/jiuyinshengong.js:20:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:356:34)\n    at PERFORM.use (/home/mud/mud/world/skill/force/jiuyinshengong.js:85:8)\n    at CHARACTER.use_pfm (/home/mud/mud/world/extends/char/auto_combat.js:85:25)\n    at CHARACTER.check_pfms (/home/mud/mud/world/extends/char/auto_combat.js:175:14)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:44:25)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-21 09:16:12] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_dodge_over (/home/mud/mud/world/skill/dodge/shaolinshenfa2.js:41:24)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:347:39)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-08-21 11:21:27] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_force_over (/home/mud/mud/world/skill/force/jiuyinshengong.js:20:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:356:34)\n    at PERFORM.use (/home/mud/mud/world/skill/emei/jiuyinbaiguzhao.js:43:20)\n    at CHARACTER.use_pfm (/home/mud/mud/world/extends/char/auto_combat.js:85:25)\n    at CHARACTER.check_pfms (/home/mud/mud/world/extends/char/auto_combat.js:175:14)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:44:25)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-21 12:40:07] 前端构建完成 da466dd（www/ 已更新）

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

✓ built in 383ms
[2026-08-21 12:45:08] 前端构建完成 da466dd（www/ 已更新）
```
