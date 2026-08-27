# 服务器运行状态

**心跳**: 2026-08-27 07:07:01 UTC / 北京时间 2026-08-27 15:07:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 17h 53m |
| 正式服(200) | running | 0 | 0 | 1d 18h 46m |

## Web 服务

- status: ok | 运行 1d 18h 46m | rss 100MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 98MB | 0d 17h 53m |
| mud-game | online | 3694 | 96MB | 1d 18h 46m |
| mud-web | online | 3604 | 100MB | 1d 18h 46m |

## 系统

- 内存: 423MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-27）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```

[31m[PARSE_ERROR] [0mUnterminated string
   [38;5;246m╭[0m[38;5;246m─[0m[38;5;246m[[0m src/dialog/score.js:4:15 [38;5;246m][0m
   [38;5;246m│[0m
 [38;5;246m4 │[0m [38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249mf[0m[38;5;249mo[0m[38;5;249mo[0m[38;5;249mt[0m[38;5;249me[0m[38;5;249mr[0m[38;5;249m:[0m[38;5;249m [0m[38;5;249m[[0m[38;5;249m[[0m"灞炴€?, null],
 [38;5;240m  │[0m               ─────────┬──────  
 [38;5;240m  │[0m                        ╰──────── 
[38;5;246m───╯[0m

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
[2026-08-27 07:05:07] 错误：前端构建失败 767c885，前端保持旧版本，下轮自动重试
```
