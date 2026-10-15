# 服务器运行状态

**心跳**: 2026-10-15 06:57:01 UTC / 北京时间 2026-10-15 14:57:01

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
| mud-game | online | 3790 | 90MB | 0d 0h 1m |
| mud-web | online | 3675 | 87MB | 0d 0h 1m |
| mud-game-test | online | 181 | 91MB | 0d 0h 1m |

## 系统

- 内存: 461MB / 3911MB
- 磁盘: 19% 已用（80G 可用）
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
  （属主类问题可用 --fix 自动修复）
[2026-10-15 06:10:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 2 项：
    1. 当前分支是 fix/net-ws-unauth-dos 而不是 main → 部署会 ff-only 合并失败或产生分叉
    2. 工作区有 1 处未提交改动 → deploy/pull.sh 会直接拒绝部署
[2026-10-15 06:20:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail

  会阻塞自动部署的问题 1 项：
    1. 当前分支是 fix/loadresource-resilience 而不是 main → 部署会 ff-only 合并失败或产生分叉
[2026-10-15 06:25:01] Repo ownership/state precheck failed; see above lines. Run check_repo_ownership.js for detail
[2026-10-15 06:30:01] Dirty checkout; deployment refused
[2026-10-15 06:34:33] Verified release 3fb6a9a1940098f349b72e1fd9b2f9d3fc7ad6ff on web and both game services
[2026-10-15 06:45:01] Dirty checkout; deployment refused
[2026-10-15 06:50:16] Verified release 15aadd470b9c4d811c502b145ef521497b1ef420 on web and both game services
[2026-10-15 06:52:24] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 06:52:24] package-lock.json 未变化且依赖自检通过，跳过 npm ci
[2026-10-15 06:52:24] Dirty checkout; deployment refused
[2026-10-15 06:53:00] Dirty checkout; deployment refused
[2026-10-15 06:55:15] Verified release 83288ee800110da089604ddc268c443d7807bc8c on web and both game services
```
