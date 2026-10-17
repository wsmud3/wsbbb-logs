# 服务器运行状态

**心跳**: 2026-10-17 23:57:02 UTC / 北京时间 2026-10-18 07:57:02

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
| mud-game | online | 3917 | 89MB | 0d 0h 1m |
| mud-web | online | 3810 | 87MB | 0d 0h 1m |
| mud-game-test | online | 323 | 127MB | 0d 0h 1m |

## 系统

- 内存: 800MB / 3911MB
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
[2026-10-17 23:10:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:10:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:15:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:15:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:20:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:20:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:25:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:25:26] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:30:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:30:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:35:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:35:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:40:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:40:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:45:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:45:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:50:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:50:27] Deployment failed at line 60; keep player database and inspect services
[2026-10-17 23:55:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-17 23:55:27] Deployment failed at line 60; keep player database and inspect services
```
