# 服务器运行状态

**心跳**: 2026-08-26 16:17:02 UTC / 北京时间 2026-08-27 00:17:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 3h 3m |
| 正式服(200) | running | 1 | 0 | 1d 3h 56m |

## Web 服务

- status: ok | 运行 1d 3h 56m | rss 100MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 96MB | 0d 3h 3m |
| mud-game | online | 3694 | 98MB | 1d 3h 56m |
| mud-web | online | 3604 | 100MB | 1d 3h 56m |

## 系统

- 内存: 431MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-26）

- warn: 0 | error: 0 | fatal: 1

### 今日 fatal（最近 10 条）

```
[2026-08-26 13:13:35] [FATAL] 未捕获异常 | {"message":"lv is not defined","stack":"ReferenceError: lv is not defined\n    at BASE.on_damage (/home/mud/mud/world/skill/force/changshengjue.js:79:32)\n    at CHARACTER.damage (/home/mud/mud/world/extends/char/combat.js:424:31)\n    at CHARACTER.do_attack (/home/mud/mud/world/extends/char/combat.js:225:25)\n    at CHARACTER.auto_attack (/home/mud/mud/world/extends/char/auto_combat.js:49:23)\n    at listOnTimeout (node:internal/timers:605:17)\n    at process.processTimers (node:internal/timers:541:7)"}
```

## 最近部署（deploy.log 末尾 20 行）

```

[31m[PARSE_ERROR] [0mUnterminated string
    [38;5;246m╭[0m[38;5;246m─[0m[38;5;246m[[0m src/dialog/channel.js:93:33 [38;5;246m][0m
    [38;5;246m│[0m
 [38;5;246m93 │[0m [38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249m [0m[38;5;249mv[0m[38;5;249ma[0m[38;5;249mr[0m[38;5;249m [0m[38;5;249mh[0m[38;5;249mt[0m[38;5;249mm[0m[38;5;249ml[0m[38;5;249m [0m[38;5;249m=[0m[38;5;249m [0m[38;5;249m[[0m[38;5;249m"[0m[38;5;249m<[0m[38;5;249m"[0m[38;5;249m,[0m[38;5;249m [0m[38;5;249mc[0m[38;5;249mo[0m[38;5;249ml[0m[38;5;249mo[0m[38;5;249mr[0m[38;5;249m,[0m[38;5;249m [0m">銆?];
 [38;5;240m   │[0m                                 ────┬───  
 [38;5;240m   │[0m                                     ╰───── 
[38;5;246m────╯[0m

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
[2026-08-26 16:15:07] 错误：前端构建失败 767c885，前端保持旧版本，下轮自动重试
```
