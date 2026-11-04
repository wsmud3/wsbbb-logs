# 服务器运行状态

**心跳**: 2026-11-04 08:32:02 UTC / 北京时间 2026-11-04 16:32:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 11h 5m |
| 正式服(200) | running | 0 | 0 | 2d 2h 16m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4300 | 95MB | 2d 2h 16m |
| mud-web | online | 4191 | 87MB | 2d 2h 16m |
| mud-game-test | online | 949 | 103MB | 0d 11h 5m |

## 系统

- 内存: 1047MB / 3911MB
- 磁盘: 22% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-11-04）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
  会阻塞自动部署的问题 1 项：
    1. 当前分支是 push/batch6 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 09:30:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-23 09:35:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 09:35:11] Verified release 9124a597d975ab1538c4bbeedfc9765529b45e9a on web and both game services
[2026-10-30 14:25:10] Deployment failed at line 21; keep player database and inspect services
[2026-11-01 05:41:10] Deployment failed at line 21; keep player database and inspect services
[2026-11-02 04:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-02 04:10:11] Verified release 82bdc1543c80bb7ad96688e59a31cae0a71fad66 on web and both game services
[2026-11-02 06:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-11-02 06:15:12] Verified release afd655fee5789f7376321685ee452d9df9924333 on web and both game services
[2026-11-04 03:30:45] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 04:55:45] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 05:25:39] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 06:40:38] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 07:00:40] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 07:20:47] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 07:40:55] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 08:00:47] Deployment failed at line 21; keep player database and inspect services
[2026-11-04 08:20:41] Deployment failed at line 21; keep player database and inspect services
```
