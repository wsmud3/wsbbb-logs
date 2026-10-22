# 服务器运行状态

**心跳**: 2026-10-22 18:37:02 UTC / 北京时间 2026-10-23 02:37:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 9h 16m |
| 正式服(200) | running | 0 | 0 | 0d 10h 6m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4260 | 100MB | 0d 10h 6m |
| mud-web | online | 4151 | 98MB | 0d 10h 6m |
| mud-game-test | online | 789 | 102MB | 0d 9h 16m |

## 系统

- 内存: 919MB / 3911MB
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
[2026-10-22 17:00:01] Dirty checkout; deployment refused
[2026-10-22 17:05:01] Dirty checkout; deployment refused
[2026-10-22 17:10:01] Dirty checkout; deployment refused
[2026-10-22 17:15:01] Dirty checkout; deployment refused
[2026-10-22 17:20:01] Dirty checkout; deployment refused
[2026-10-22 17:25:01] Dirty checkout; deployment refused
[2026-10-22 17:30:01] Dirty checkout; deployment refused
[2026-10-22 17:35:01] Dirty checkout; deployment refused
[2026-10-22 17:40:01] Dirty checkout; deployment refused
[2026-10-22 17:45:01] Dirty checkout; deployment refused
[2026-10-22 17:50:01] Dirty checkout; deployment refused
[2026-10-22 17:55:01] Dirty checkout; deployment refused
[2026-10-22 18:00:02] Dirty checkout; deployment refused
[2026-10-22 18:05:01] Dirty checkout; deployment refused
[2026-10-22 18:10:01] Dirty checkout; deployment refused
[2026-10-22 18:15:01] Dirty checkout; deployment refused
[2026-10-22 18:20:01] Dirty checkout; deployment refused
[2026-10-22 18:25:01] Dirty checkout; deployment refused
[2026-10-22 18:30:01] Dirty checkout; deployment refused
[2026-10-22 18:35:01] Dirty checkout; deployment refused
```
