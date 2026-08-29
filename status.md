# 服务器运行状态

**心跳**: 2026-08-29 09:42:01 UTC / 北京时间 2026-08-29 17:42:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 0 | 0 | 2d 20h 28m |
| 正式服(200) | running | 0 | 0 | 3d 21h 21m |

## Web 服务

- status: ok | 运行 3d 21h 21m | rss 101MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 100MB | 2d 20h 28m |
| mud-game | online | 3694 | 97MB | 3d 21h 21m |
| mud-web | online | 3604 | 101MB | 3d 21h 21m |

## 系统

- 内存: 508MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-29）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```

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
[2026-08-29 09:05:13] 错误：前端构建失败 41b7356，前端保持旧版本，下轮自动重试
[2026-08-29 09:05:13] 中止：前端构建失败，暂不 reload，等待下一轮重试
[2026-08-29 09:10:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:15:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:20:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:25:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:30:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:35:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
[2026-08-29 09:40:01] 跳过：工作区不干净（存在未提交改动），拒绝自动部署
```
