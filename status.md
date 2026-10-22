# 服务器运行状态

**心跳**: 2026-10-22 06:07:02 UTC / 北京时间 2026-10-22 14:07:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 1 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4242 | 91MB | 0d 0h 1m |
| mud-web | online | 4135 | 87MB | 0d 0h 1m |
| mud-game-test | online | 727 | 93MB | 0d 0h 1m |

## 系统

- 内存: 919MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-22 04:40:12] Verified release d675f3bbe338e033f7e9cb86b798d7959c8081a4 on web and both game services
[2026-10-22 04:50:01] Dirty checkout; deployment refused
[2026-10-22 04:55:01] Dirty checkout; deployment refused
[2026-10-22 05:00:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:00:12] Verified release 24e0c84413432d557da2dcabf0d0dcbfe2a140c3 on web and both game services
[2026-10-22 05:10:01] Dirty checkout; deployment refused
[2026-10-22 05:15:01] Dirty checkout; deployment refused
[2026-10-22 05:20:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:20:11] Verified release 70c9307ba0cc9e2390a250f47bb7faa4086a6422 on web and both game services
[2026-10-22 05:25:02] Dirty checkout; deployment refused
[2026-10-22 05:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:30:12] Verified release 909ec83d702485569bf2b41aaee03bc6ebea74db on web and both game services
[2026-10-22 05:35:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:35:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-22 05:40:13] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 05:40:17] Verified release 8ed514400234ef0df2dbe25c2971df1934f8a811 on web and both game services
[2026-10-22 06:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:00:11] Verified release 3a1004d8cb69c380dd5e6bcf36ad80a012f4b5cb on web and both game services
[2026-10-22 06:05:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 06:05:10] Verified release aa018a1c69c804310128512d01aa20f5cb852c34 on web and both game services
```
