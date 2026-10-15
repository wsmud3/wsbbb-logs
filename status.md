# 服务器运行状态

**心跳**: 2026-10-15 06:22:02 UTC / 北京时间 2026-10-15 14:22:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 0d 0h 1m |
| 正式服(200) | running | 0 | 0 | 0d 0h 4m |

## Web 服务

- status: ok | 运行 ? | rss 0MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game | online | 3781 | 90MB | 0d 0h 4m |
| mud-web | online | 3669 | 88MB | 0d 0h 12m |
| mud-game-test | online | 155 | 124MB | 0d 0h 1m |

## 系统

- 内存: 491MB / 3911MB
- 磁盘: 19% 已用（79G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-10-15）

- warn: 0 | error: 0 | fatal: 7

### 今日 fatal（最近 10 条）

```
[2026-10-15 06:12:31] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud-test/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud-test/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:13:32] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud-test/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud-test/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:13:42] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:14:24] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:14:25] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud-test/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud-test/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:14:44] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
[2026-10-15 06:14:55] [FATAL] 未捕获异常 | {"message":"server.onTcpReceive is not a function","stack":"TypeError: server.onTcpReceive is not a function\n    at Object.readData (/home/mud/mud/os/net-ws.js:378:24)\n    at Socket.<anonymous> (/home/mud/mud/os/net-ws.js:74:33)\n    at Socket.emit (node:events:509:28)\n    at addChunk (node:internal/streams/readable:563:12)\n    at readableAddChunkPushByteMode (node:internal/streams/readable:514:3)\n    at Readable.push (node:internal/streams/readable:394:5)\n    at TCP.onStreamRead (node:internal/stream_base_commons:189:23)"}
```

## 最近部署（deploy.log 末尾 20 行）

```
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

  会阻塞自动部署的问题 2 项：
    1. 当前分支是 fix/net-ws-unauth-dos 而不是 main → 部署会 ff-only 合并失败或产生分叉
    2. 工作区有 1 处未提交改动 → deploy/pull.sh 会直接拒绝部署
[2026-10-15 06:20:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
```
