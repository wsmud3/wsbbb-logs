# 服务器运行状态

**心跳**: 2026-10-14 07:32:01 UTC / 北京时间 2026-10-14 15:32:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 0m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3725 | 115MB | 0d 0h 0m |
| mud-web | online | 3627 | 95MB | 0d 0h 0m |
| mud-game-test | online | 46 | 122MB | 0d 0h 1m |

## 系统

- 内存: 507MB / 3911MB
- 磁盘: 19% 已用（80G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-14）

- warn: 0 | error: 2 | fatal: 0

### 今日 error（最近 10 条）

```
[2026-10-14 03:45:59] [ERROR] 未处理的Promise拒绝 | {"reason":"SqliteError: unable to open database file"}
[2026-10-14 03:46:07] [ERROR] 未处理的Promise拒绝 | {"reason":"SqliteError: unable to open database file"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-14 06:09:05] Dirty checkout; deployment refused
[2026-10-14 06:10:01] Dirty checkout; deployment refused
[2026-10-14 06:15:01] Dirty checkout; deployment refused
[2026-10-14 06:20:01] Dirty checkout; deployment refused
[2026-10-14 06:25:01] Dirty checkout; deployment refused
[2026-10-14 06:30:01] Dirty checkout; deployment refused
[2026-10-14 06:35:01] Dirty checkout; deployment refused
[2026-10-14 06:40:01] Dirty checkout; deployment refused
[2026-10-14 06:45:01] Dirty checkout; deployment refused
[2026-10-14 06:50:01] Dirty checkout; deployment refused
[2026-10-14 06:50:18] Dirty checkout; deployment refused
[2026-10-14 06:55:01] Dirty checkout; deployment refused
[2026-10-14 07:00:01] Dirty checkout; deployment refused
[2026-10-14 07:05:01] Dirty checkout; deployment refused
[2026-10-14 07:10:01] Dirty checkout; deployment refused
[2026-10-14 07:15:01] Dirty checkout; deployment refused
[2026-10-14 07:20:01] Dirty checkout; deployment refused
[2026-10-14 07:25:01] Dirty checkout; deployment refused
[2026-10-14 07:29:14] Dirty checkout; deployment refused
[2026-10-14 07:30:01] Dirty checkout; deployment refused
```
