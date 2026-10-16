# 服务器运行状态

**心跳**: 2026-10-16 06:22:02 UTC / 北京时间 2026-10-16 14:22:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 2h 11m |
| 正式服(200) | running | 0 | 0 | 0d 2h 11m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3805 | 87MB | 0d 2h 11m |
| mud-web | online | 3698 | 81MB | 0d 2h 11m |
| mud-game-test | online | 211 | 91MB | 0d 2h 11m |

## 系统

- 内存: 712MB / 3911MB
- 磁盘: 21% 已用（78G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-16）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
  会阻塞自动部署的问题 1 项：
    1. 工作区有 1 处未提交改动 → deploy/pull.sh 会直接拒绝部署
[2026-10-15 07:45:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-15 07:50:01] Dirty checkout; deployment refused

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 feat/chatlog-and-bot-commands 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-15 07:55:02] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-15 08:00:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 08:00:11] Verified release 91b6918a8701431633d8892c34f238ec59b4ad04 on web and both game services
[2026-10-15 08:10:02] Dirty checkout; deployment refused
[2026-10-15 08:15:06] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 08:15:10] Verified release dce8d73ab10520485f8299087cd818b3a948d5ce on web and both game services
[2026-10-15 08:20:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 08:20:12] Verified release 8b982058f8a2a31f856bfb62830721b06878b1e5 on web and both game services
[2026-10-16 03:50:01] Dirty checkout; deployment refused
[2026-10-16 03:55:01] Dirty checkout; deployment refused
[2026-10-16 04:05:17] Verified release 8b7b90eb5f55f4f4481045adb02d2b3a302abac6 on web and both game services
[2026-10-16 04:10:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-16 04:10:11] Verified release 193c6d9bf81d20db5a94f7604f529a38dbe0138b on web and both game services
```
