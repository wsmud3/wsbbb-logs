# 服务器运行状态

**心跳**: 2026-10-22 05:12:02 UTC / 北京时间 2026-10-22 13:12:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 3m |
| 正式服(200) | running | 0 | 0 | 0d 0h 11m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4236 | 94MB | 0d 0h 11m |
| mud-web | online | 4129 | 89MB | 0d 0h 11m |
| mud-game-test | online | 715 | 94MB | 0d 0h 3m |

## 系统

- 内存: 925MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-22 03:40:10] Verified release 6c9cdcb5b5eaa95b3b8370bf3564e58639eb19d7 on web and both game services
[2026-10-22 03:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 03:45:11] Verified release 2d65019aea5807f9c9110838d325af0ad290bd89 on web and both game services
[2026-10-22 03:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 03:50:10] Verified release ed3617207fa649685b4617426c9c05c38d2e5ef8 on web and both game services
[2026-10-22 04:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 04:00:12] Verified release 1888a05fb22ceaa344ffcbd28c65c7f0feb906b3 on web and both game services
[2026-10-22 04:15:01] Dirty checkout; deployment refused
[2026-10-22 04:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 04:20:11] Verified release 38e4cbe394736c9d3971c09b95e0e44c6f8c957e on web and both game services
[2026-10-22 04:25:01] Dirty checkout; deployment refused
[2026-10-22 04:30:01] Dirty checkout; deployment refused
[2026-10-22 04:35:01] Dirty checkout; deployment refused
[2026-10-22 04:40:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 04:40:12] Verified release d675f3bbe338e033f7e9cb86b798d7959c8081a4 on web and both game services
[2026-10-22 04:50:01] Dirty checkout; deployment refused
[2026-10-22 04:55:01] Dirty checkout; deployment refused
[2026-10-22 05:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:00:12] Verified release 24e0c84413432d557da2dcabf0d0dcbfe2a140c3 on web and both game services
[2026-10-22 05:10:01] Dirty checkout; deployment refused
```
