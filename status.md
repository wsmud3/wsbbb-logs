# 服务器运行状态

**心跳**: 2026-08-29 10:32:02 UTC / 北京时间 2026-08-29 18:32:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 3 | 2 | 2d 21h 18m |
| 正式服(200) | running | 0 | 0 | 3d 22h 11m |

## Web 服务

- status: ok | 运行 3d 22h 11m | rss 98MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3771 | 101MB | 2d 21h 18m |
| mud-game | online | 3694 | 92MB | 3d 22h 11m |
| mud-web | online | 3604 | 98MB | 3d 22h 11m |

## 系统

- 内存: 626MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-29）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
    at #build (file:///home/mud/mud/node_modules/rolldown/dist/shared/rolldown-build-9MccaWPU.mjs:3236:34)
    at async buildEnvironment (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33137:64)
    at async Object.build (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33559:19)
    at async Object.buildApp (file:///home/mud/mud/node_modules/vite/dist/node/chunks/node.js:33556:153)
    at async CAC.<anonymous> (file:///home/mud/mud/node_modules/vite/dist/node/cli.js:777:3) {
  errors: [Getter/Setter]
}
[2026-08-29 09:45:07] 错误：前端构建失败 f32380f，前端保持旧版本，下轮自动重试
[2026-08-29 09:45:07] 中止：前端构建失败，暂不 reload，等待下一轮重试
[2026-08-29 09:50:01] 恢复被删除的前端产物 www/assets/index-BFIScYUv.css
[2026-08-29 09:50:01] 恢复被删除的前端产物 www/assets/index-BTPjB4UD.js
[2026-08-29 09:50:06] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 09:55:06] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:00:10] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:05:05] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:10:07] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:15:07] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:20:07] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:25:07] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
[2026-08-29 10:30:05] 前端产物校验通过 f32380f（使用仓库内版本，跳过服务器构建）
```
