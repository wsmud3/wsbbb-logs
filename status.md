# 服务器运行状态

**心跳**: 2026-08-25 12:27:01 UTC / 北京时间 2026-08-25 20:27:01

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 1 | 0 | 0d 0h 6m |
| 正式服(200) | running | 0 | 0 | 0d 0h 6m |

## Web 服务

- status: ok | 运行 0d 0h 6m | rss 88MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3770 | 88MB | 0d 0h 6m |
| mud-game | online | 3694 | 88MB | 0d 0h 6m |
| mud-web | online | 3604 | 88MB | 0d 0h 6m |

## 系统

- 内存: 404MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-25）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
✓ built in 384ms
[2026-08-25 12:20:11] 前端构建完成 3aa76b6（www/ 已更新）
[2026-08-25 12:20:23] 更新至 3aa76b6（快进合并），健康检查通过，已 pm2 reload

> msmud@0.0.1 build
> vite build

vite v8.0.14 building client environment for production...
[2Ktransforming...✓ 59 modules transformed.
rendering chunks...
computing gzip size...
www/index.html                                           0.42 kB │ gzip:   0.29 kB
www/assets/glyphicons-halflings-regular-BUJKDMgK.eot    20.12 kB
www/assets/glyphicons-halflings-regular-BKjkU69z.woff   23.42 kB
www/assets/glyphicons-halflings-regular-DrwTMapi.ttf    45.40 kB
www/assets/index-xwkqL7qP.css                           21.16 kB │ gzip:   4.94 kB
www/assets/index-CR1bjm_l.js                           356.54 kB │ gzip: 100.48 kB

✓ built in 422ms
[2026-08-25 12:25:09] 前端构建完成 3aa76b6（www/ 已更新）
```
