# 服务器运行状态

**心跳**: 2026-10-14 17:52:02 UTC / 北京时间 2026-10-15 01:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 8h 22m |
| 正式服(200) | running | 0 | 0 | 0d 8h 22m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3758 | 98MB | 0d 8h 22m |
| mud-web | online | 3653 | 96MB | 0d 8h 37m |
| mud-game-test | online | 104 | 101MB | 0d 8h 22m |

## 系统

- 内存: 488MB / 3911MB
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
[2026-10-14 16:15:01] Dirty checkout; deployment refused
[2026-10-14 16:20:01] Dirty checkout; deployment refused
[2026-10-14 16:25:01] Dirty checkout; deployment refused
[2026-10-14 16:30:01] Dirty checkout; deployment refused
[2026-10-14 16:35:02] Dirty checkout; deployment refused
[2026-10-14 16:40:01] Dirty checkout; deployment refused
[2026-10-14 16:45:01] Dirty checkout; deployment refused
[2026-10-14 16:50:01] Dirty checkout; deployment refused
[2026-10-14 16:55:01] Dirty checkout; deployment refused
[2026-10-14 17:00:01] Dirty checkout; deployment refused
[2026-10-14 17:05:01] Dirty checkout; deployment refused
[2026-10-14 17:10:01] Dirty checkout; deployment refused
[2026-10-14 17:15:02] Dirty checkout; deployment refused
[2026-10-14 17:20:02] Dirty checkout; deployment refused
[2026-10-14 17:25:01] Dirty checkout; deployment refused
[2026-10-14 17:30:01] Dirty checkout; deployment refused
[2026-10-14 17:35:01] Dirty checkout; deployment refused
[2026-10-14 17:40:01] Dirty checkout; deployment refused
[2026-10-14 17:45:01] Dirty checkout; deployment refused
[2026-10-14 17:50:01] Dirty checkout; deployment refused
```
