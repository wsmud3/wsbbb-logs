# 服务器运行状态

**心跳**: 2026-10-15 06:12:02 UTC / 北京时间 2026-10-15 14:12:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 2m |
| 正式服(200) | running | 0 | 0 | 0d 0h 2m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3775 | 93MB | 0d 0h 2m |
| mud-web | online | 3669 | 87MB | 0d 0h 2m |
| mud-game-test | online | 149 | 92MB | 0d 0h 2m |

## 系统

- 内存: 463MB / 3911MB
- 磁盘: 19% 已用（79G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-15）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-15 05:40:05] Deployment failed at line 18; keep player database and inspect services
[2026-10-15 05:42:01] Verified release 3d447af90abff5422c178d8766da32d425bb3077 on web and both game services
[2026-10-15 05:45:12] Deployment failed at line 34; keep player database and inspect services
[2026-10-15 05:45:46] Verified release b6a9024f1424ca49509b9730a1272eae051e1b76 on web and both game services
[2026-10-15 05:55:05] Deployment failed at line 18; keep player database and inspect services
[2026-10-15 05:56:47] Dirty checkout; deployment refused
[2026-10-15 05:58:11] Verified release f6772cb7531132e14695a8aba8a50a9b18d4ee2c on web and both game services
[2026-10-15 06:06:45] Dirty checkout; deployment refused
[2026-10-15 06:06:45] Dirty checkout; deployment refused
[2026-10-15 06:09:56] Verified release 23e4882fb62c0960f6a99318047375e56700fff9 on web and both game services

  会阻塞自动部署的问题 1 项：
    1. 1 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
  （属主类问题可用 --fix 自动修复）
[2026-10-15 06:09:57] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 1 项：
    1. 1 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
  （属主类问题可用 --fix 自动修复）
[2026-10-15 06:10:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
```
