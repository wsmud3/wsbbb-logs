# 服务器运行状态

**心跳**: 2026-10-23 10:02:02 UTC / 北京时间 2026-10-23 18:02:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 26m |
| 正式服(200) | running | 0 | 0 | 0d 0h 26m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 4298 | 94MB | 0d 0h 26m |
| mud-web | online | 4189 | 90MB | 0d 0h 26m |
| mud-game-test | online | 941 | 97MB | 0d 0h 26m |

## 系统

- 内存: 920MB / 3911MB
- 磁盘: 21% 已用（77G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-10-23 07:55:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 07:55:11] Verified release 8357fc1e91c7ca20c725d5daf17a33874c749c92 on web and both game services
[2026-10-23 08:10:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 08:10:12] Verified release a18ab0a6de51198b3edb2ccba188eff0cd9903b6 on web and both game services
[2026-10-23 08:15:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 08:15:12] Verified release 5083ee0f9dcaf69e95acd11a688d935e8972f78b on web and both game services
[2026-10-23 08:25:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 08:25:12] Verified release f7f4e8895019cf1c438634481330ed6a905d22c3 on web and both game services
[2026-10-23 08:30:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 08:30:11] Verified release 59a9ee70346c0e497bc24955a24edf48aec4a929 on web and both game services
[2026-10-23 08:55:07] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 08:55:12] Verified release 340ce762879139b92ec51aa2e14055c1275f711e on web and both game services
[2026-10-23 09:25:14] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 09:25:18] Verified release 854145650d9e72633c3eb23a6f03a9ef41a542d8 on web and both game services

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 push/batch6 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-23 09:30:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-23 09:35:08] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-23 09:35:11] Verified release 9124a597d975ab1538c4bbeedfc9765529b45e9a on web and both game services
```
