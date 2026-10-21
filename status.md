# 服务器运行状态

**心跳**: 2026-10-21 21:57:02 UTC / 北京时间 2026-10-22 05:57:03

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 12h 54m |
| 正式服(200) | running | 0 | 0 | 2d 15h 49m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4224 | 98MB | 2d 15h 49m |
| mud-web | online | 4117 | 100MB | 2d 15h 49m |
| mud-game-test | online | 672 | 101MB | 0d 12h 54m |

## 系统

- 内存: 944MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-21）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
  （属主类问题可用 --fix 自动修复）
[2026-10-21 21:40:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 2 项：
    1. 8 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
  （属主类问题可用 --fix 自动修复）
[2026-10-21 21:45:02] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 2 项：
    1. 8 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
  （属主类问题可用 --fix 自动修复）
[2026-10-21 21:50:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 2 项：
    1. 8 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
  （属主类问题可用 --fix 自动修复）
[2026-10-21 21:55:02] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
```
