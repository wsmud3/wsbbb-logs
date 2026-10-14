# 服务器运行状态

**心跳**: 2026-10-14 10:02:02 UTC / 北京时间 2026-10-14 18:02:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 32m |
| 正式服(200) | running | 0 | 0 | 0d 0h 32m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3758 | 91MB | 0d 0h 32m |
| mud-web | online | 3653 | 89MB | 0d 0h 47m |
| mud-game-test | online | 104 | 91MB | 0d 0h 32m |

## 系统

- 内存: 457MB / 3911MB
- 磁盘: 19% 已用（80G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-14）

- warn: 0 | error: 3 | fatal: 0

### 今日 error（最近 10 条）

```
[2026-10-14 03:45:59] [ERROR] 未处理的Promise拒绝 | {"reason":"SqliteError: unable to open database file"}
[2026-10-14 03:46:07] [ERROR] 未处理的Promise拒绝 | {"reason":"SqliteError: unable to open database file"}
[2026-10-14 07:36:04] [ERROR] 未处理的Promise拒绝 | {"reason":"Error: Could not locate the bindings file. Tried:\n → /home/mud/mud/node_modules/better-sqlite3/build/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/build/Debug/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/build/Release/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/out/Debug/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/Debug/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/out/Release/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/Release/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/build/default/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/compiled/24.18.0/linux/x64/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/addon-build/release/install-root/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/addon-build/debug/install-root/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/addon-build/default/install-root/better_sqlite3.node\n → /home/mud/mud/node_modules/better-sqlite3/lib/binding/node-v137-linux-x64/better_sqlite3.node"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-14 08:00:17] Verified release abffbf063f0e667e3bbc5fe3019cb03b1b361d63 on web and both game services
[2026-10-14 08:14:45] Verified release 117a89846616546067867f10da3302660fa77139 on web and both game services
[2026-10-14 08:25:01] Dirty checkout; deployment refused
[2026-10-14 08:30:01] Dirty checkout; deployment refused
[2026-10-14 08:34:12] Verified release 9a5d88ae8224251e53631d11612681f43d95e507 on web and both game services
[2026-10-14 08:45:16] Verified release d662114632958b5623bcab8f933d2629e7f85ed4 on web and both game services
[2026-10-14 09:10:02] Dirty checkout; deployment refused
[2026-10-14 09:13:17] Deployment failed at line 35; keep player database and inspect services
[2026-10-14 09:14:14] Verified release d7399b5023cba659df32455d67c9e16fd3e9fdf2 on web and both game services
[2026-10-14 09:14:28] Dirty checkout; deployment refused
[2026-10-14 09:15:01] Dirty checkout; deployment refused
[2026-10-14 09:20:01] Dirty checkout; deployment refused
[2026-10-14 09:25:01] Dirty checkout; deployment refused
[2026-10-14 09:30:01] Dirty checkout; deployment refused
[2026-10-14 09:35:01] Dirty checkout; deployment refused
[2026-10-14 09:40:01] Dirty checkout; deployment refused
[2026-10-14 09:45:01] Dirty checkout; deployment refused
[2026-10-14 09:50:01] Dirty checkout; deployment refused
[2026-10-14 09:55:01] Dirty checkout; deployment refused
[2026-10-14 10:00:01] Dirty checkout; deployment refused
```
