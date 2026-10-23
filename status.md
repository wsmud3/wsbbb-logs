# 服务器运行状态

**心跳**: 2026-10-23 07:52:02 UTC / 北京时间 2026-10-23 15:52:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 21m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4290 | 93MB | 0d 0h 21m |
| mud-web | online | 4181 | 89MB | 0d 0h 21m |
| mud-game-test | online | 926 | 125MB | 0d 0h 1m |

## 系统

- 内存: 1003MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 07:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:20:12] Verified release 615b6ced06ca53b51bceb9b103203d22db4dc85a on web and both game services
[2026-10-23 07:30:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:30:11] Verified release 85bb0e38d6e095bf82786a7dc69a4207713bebc2 on web and both game services

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 07:35:02] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 07:40:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 07:45:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 push/batch2 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 07:50:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
```
