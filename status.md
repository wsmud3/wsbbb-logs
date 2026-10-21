# 服务器运行状态

**心跳**: 2026-10-21 07:22:03 UTC / 北京时间 2026-10-21 15:22:03

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 0m |
| 正式服(200) | running | 0 | 0 | 2d 1h 14m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4224 | 100MB | 2d 1h 14m |
| mud-web | online | 4117 | 99MB | 2d 1h 14m |
| mud-game-test | online | 662 | 128MB | 0d 0h 0m |

## 系统

- 内存: 987MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-21）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-19 00:57:27] Verified release 2a55adcd2a5e01e9b0ae130695c98cabc4c3bdd6 on web and both game services
[2026-10-19 02:00:50] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 02:00:54] Verified release 96e584b2166a2aaa5695c49092b5804fb0c6b6cc on web and both game services
[2026-10-19 02:02:54] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 02:02:57] Verified release 6865733e07ee0bb644e123753d37699b2048eaad on web and both game services
[2026-10-19 06:06:32] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 06:06:53] Deployment failed at line 60; keep player database and inspect services
[2026-10-19 06:07:56] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-19 06:07:59] Verified release c4dc4c94dbf367773fbdf1d2f62db12b0a4af1fe on web and both game services
[2026-10-21 06:55:06] Deployment failed at line 24; keep player database and inspect services
[2026-10-21 07:00:10] Deployment failed at line 24; keep player database and inspect services
[2026-10-21 07:05:06] Deployment failed at line 24; keep player database and inspect services
[2026-10-21 07:10:06] Deployment failed at line 24; keep player database and inspect services
[2026-10-21 07:15:03] Dirty checkout; deployment refused

  会阻塞自动部署的问题 2 项：
    1. 8 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
  （属主类问题可用 --fix 自动修复）
[2026-10-21 07:20:03] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
```
