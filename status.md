# 服务器运行状态

**心跳**: 2026-08-26 23:32:01 UTC / 北京时间 2026-08-27 07:32:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 3 | 0 | 0d 10h 18m |
| 正式服(200) | running | 0 | 0 | 1d 11h 11m |

## Web 服务

- status: ok | 运行 1d 11h 11m | rss 99MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 98MB | 0d 10h 18m |
| mud-game | online | 3694 | 96MB | 1d 11h 11m |
| mud-web | online | 3604 | 99MB | 1d 11h 11m |

## 系统

- 内存: 437MB / 3911MB
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
[2026-08-26 23:30:06] 错误：前端构建失败 767c885，前端保持旧版本，下轮自动重试
```
