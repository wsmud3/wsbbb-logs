# 服务器运行状态

**心跳**: 2026-10-22 03:07:02 UTC / 北京时间 2026-10-22 11:07:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 21m |
| 正式服(200) | running | 1 | 0 | 0d 0h 21m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4225 | 94MB | 0d 0h 21m |
| mud-web | online | 4118 | 89MB | 0d 0h 21m |
| mud-game-test | online | 678 | 94MB | 0d 0h 21m |

## 系统

- 内存: 895MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
    3. 工作区有 1 处未提交改动 → deploy/pull.sh 会直接拒绝部署
  （属主类问题可用 --fix 自动修复）
[2026-10-22 02:25:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 3 项：
    1. 18 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
    3. 工作区有 1 处未提交改动 → deploy/pull.sh 会直接拒绝部署
  （属主类问题可用 --fix 自动修复）
[2026-10-22 02:30:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 2 项：
    1. 14 个已跟踪文件/目录的属主不是 mud → git 无法覆盖它们，部署会在"恰好要改到它们"时失败
    2. 当前分支是 feat/kw-faithful-rebuild 而不是 main → 部署会 ff-only 合并失败或产生分叉
  （属主类问题可用 --fix 自动修复）
[2026-10-22 02:35:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-22 02:40:01] Dirty checkout; deployment refused
[2026-10-22 02:45:12] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-22 02:45:17] Verified release 5bfcdd1c54846f4ffca6dca7e24015c1082c0df6 on web and both game services
```
