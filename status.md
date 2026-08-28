# 服务器运行状态

**心跳**: 2026-08-28 16:52:01 UTC / 北京时间 2026-08-29 00:52:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 2d 3h 38m |
| 正式服(200) | running | 0 | 0 | 3d 4h 31m |

## Web 服务

- status: ok | 运行 3d 4h 31m | rss 94MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 99MB | 2d 3h 38m |
| mud-game | online | 3694 | 97MB | 3d 4h 31m |
| mud-web | online | 3604 | 94MB | 3d 4h 31m |

## 系统

- 内存: 431MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-28）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```

[31m[PARSE_ERROR] [0mUnterminated string
     [38;5;246m╭[0m[38;5;246m─[0m[38;5;246m[[0m src/dialog/message.js:154:18 [38;5;246m][0m
     [38;5;246m│[0m
 [38;5;246m154 │[0m [38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249ms[0m[38;5;249mt[0m[38;5;249mr[0m[38;5;249m.[0m[38;5;249mp[0m[38;5;249mu[0m[38;5;249ms[0m[38;5;249mh[0m[38;5;249m([0m"骞?);
 [38;5;240m    │[0m                  ────┬──  
 [38;5;240m    │[0m                      ╰──── 
[38;5;246m─────╯[0m

...
    at aggregateBindingErrorsIntoJsError (file:///home/mud/mud/node_modules/rolldown/dist/shared/error-B8po7KiL.mjs:48:18)
    at unwrapBindingResult (file:///home/mud/mud/node_modules/rolldown/dist/shared/error-B8po7KiL.mjs:18:128)
    at #build (file:///home/mud/mud/node_modules/rolldown/dist/shared/rolldown-build-9MccaWPU.mjs:3236:34)
    at async buildEnvironment (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33137:64)
    at async Object.build (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33559:19)
    at async Object.buildApp (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33556:153)
    at async CAC.<anonymous> (file:///home/mud/mud/node_modules/vite/dist/node/cli.js:777:3) {
  errors: [Getter/Setter]
}
[2026-08-28 16:50:07] 错误：前端构建失败 2773c3b，前端保持旧版本，下轮自动重试
```
