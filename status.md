# 服务器运行状态

**心跳**: 2026-10-22 09:32:02 UTC / 北京时间 2026-10-22 17:32:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 11m |
| 正式服(200) | running | 0 | 0 | 0d 1h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4260 | 94MB | 0d 1h 1m |
| mud-web | online | 4151 | 91MB | 0d 1h 1m |
| mud-game-test | online | 789 | 95MB | 0d 0h 11m |

## 系统

- 内存: 909MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 6

### 今日 fatal（最近 10 条）

```
[2026-10-22 08:07:10] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud-test/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud-test/os/char/npc.js:127:29)\n    at CHARACTER.end_attack (/home/mud/mud-test/os/char/combat.js:193:41)\n    at CHARACTER.auto_attack (/home/mud/mud-test/world/extends/char/auto_combat.js:57:26)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-22 08:07:11] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud-test/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud-test/os/char/npc.js:127:29)\n    at CHARACTER.end_attack (/home/mud/mud-test/os/char/combat.js:193:41)\n    at CHARACTER.auto_attack (/home/mud/mud-test/world/extends/char/auto_combat.js:11:27)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-22 08:07:51] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud/os/char/npc.js:127:29)\n    at CHARACTER.query_enemy (/home/mud/mud/os/char/combat.js:159:31)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:8:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-22 08:08:31] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud/os/char/npc.js:127:29)\n    at CHARACTER.query_enemy (/home/mud/mud/os/char/combat.js:159:31)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:8:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-22 08:08:32] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud/os/char/npc.js:127:29)\n    at CHARACTER.query_enemy (/home/mud/mud/os/char/combat.js:159:31)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:8:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
[2026-10-22 08:09:01] [FATAL] 未捕获异常 | {"message":"room.send_room is not a function","stack":"TypeError: room.send_room is not a function\n    at NPC.on_die (/home/mud/mud-test/world/npc/wf/wenfangda.js:64:14)\n    at NPC.die (/home/mud/mud-test/os/char/npc.js:127:29)\n    at CHARACTER.end_attack (/home/mud/mud-test/os/char/combat.js:193:41)\n    at CHARACTER.auto_attack (/home/mud/mud-test/world/extends/char/auto_combat.js:57:26)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-22 07:55:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 07:55:12] Verified release a384aad852ca90f2f244f575d819972a723cb2ef on web and both game services
[2026-10-22 08:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 08:00:10] Verified release 769e4ec8dee8b8b2c0a67af20fab7cbd6a6507dc on web and both game services
[2026-10-22 08:05:01] Dirty checkout; deployment refused
[2026-10-22 08:10:02] Dirty checkout; deployment refused
[2026-10-22 08:15:01] Dirty checkout; deployment refused
[2026-10-22 08:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 08:20:11] Verified release af6e6318fe7d37e188b62adf3dacc4220a83c63d on web and both game services
[2026-10-22 08:25:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 08:25:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-22 08:30:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 08:30:10] Verified release 90a5e646156336a8d19a3407cdaa0883174b16f3 on web and both game services
[2026-10-22 09:00:01] Dirty checkout; deployment refused
[2026-10-22 09:05:01] Dirty checkout; deployment refused
[2026-10-22 09:10:01] Dirty checkout; deployment refused
[2026-10-22 09:15:01] Dirty checkout; deployment refused
[2026-10-22 09:20:01] Dirty checkout; deployment refused
[2026-10-22 09:25:01] Dirty checkout; deployment refused
[2026-10-22 09:30:02] Dirty checkout; deployment refused
```
