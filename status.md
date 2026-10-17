# 服务器运行状态

**心跳**: 2026-10-17 15:07:02 UTC / 北京时间 2026-10-17 23:07:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 1m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3811 | 89MB | 0d 0h 1m |
| mud-web | online | 3704 | 88MB | 0d 0h 1m |
| mud-game-test | online | 217 | 92MB | 0d 0h 1m |

## 系统

- 内存: 730MB / 3911MB
- 磁盘: 21% 已用（78G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-17）

- warn: 0 | error: 1 | fatal: 0

### 今日 error（最近 10 条）

```
[2026-10-17 01:07:35] [ERROR] 未处理的Promise拒绝 | {"reason":"ReferenceError: pars is not defined"}
```

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-15 08:15:10] Verified release dce8d73ab10520485f8299087cd818b3a948d5ce on web and both game services
[2026-10-15 08:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 08:20:12] Verified release 8b982058f8a2a31f856bfb62830721b06878b1e5 on web and both game services
[2026-10-16 03:50:01] Dirty checkout; deployment refused
[2026-10-16 03:55:01] Dirty checkout; deployment refused
[2026-10-16 04:05:17] Verified release 8b7b90eb5f55f4f4481045adb02d2b3a302abac6 on web and both game services
[2026-10-16 04:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-16 04:10:11] Verified release 193c6d9bf81d20db5a94f7604f529a38dbe0138b on web and both game services
[2026-10-17 14:40:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 14:40:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 14:45:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 14:45:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 14:50:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 14:50:28] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 14:55:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 14:55:29] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 15:00:13] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 15:00:33] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 15:05:09] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 15:05:30] Deployment failed at line 60; keep player database and inspect services
```
