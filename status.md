# 服务器运行状态

**心跳**: 2026-08-23 05:17:02 UTC / 北京时间 2026-08-23 13:17:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 2 | 0 | 0d 3h 46m |
| 正式服(200) | running | 0 | 0 | 0d 3h 46m |

## Web 服务

- status: ok | 运行 0d 3h 46m | rss 95MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3750 | 94MB | 0d 3h 46m |
| mud-game | online | 3679 | 90MB | 0d 3h 46m |
| mud-web | online | 3589 | 95MB | 0d 3h 46m |

## 系统

- 内存: 444MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-23）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-23 05:10:10] 前端构建完成 b8ad7e4（www/ 已更新）

> msmud@0.0.1 build
> vite build

vite v8.0.14 building client environment for production...
[2Ktransforming...
../fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular referenced in ../fonts/glyphicons-halflings-regular.svg didn't resolve at build time, it will remain unchanged to be resolved at runtime
✓ 59 modules transformed.
rendering chunks...
computing gzip size...
www/index.html                                           0.42 kB │ gzip:   0.29 kB
www/assets/glyphicons-halflings-regular-BUJKDMgK.eot    20.12 kB
www/assets/glyphicons-halflings-regular-BKjkU69z.woff   23.42 kB
www/assets/glyphicons-halflings-regular-DrwTMapi.ttf    45.40 kB
www/assets/index-CBFwBfKv.css                           21.25 kB │ gzip:   4.96 kB
www/assets/index-WuC3f3_8.js                           355.83 kB │ gzip: 100.36 kB

✓ built in 442ms
[2026-08-23 05:15:06] 前端构建完成 b8ad7e4（www/ 已更新）
```
