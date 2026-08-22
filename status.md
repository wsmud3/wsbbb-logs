# 服务器运行状态

**心跳**: 2026-08-22 02:22:02 UTC / 北京时间 2026-08-22 10:22:02

## 游戏服

| 服务器 | 状态 | 在线 | 连接 | 运行时长 |
| --- | --- | --- | --- | --- |
| 本地测试(100) | running | 3 | 1 | 0d 4h 31m |
| 正式服(200) | running | 0 | 0 | 0d 16h 50m |

## Web 服务

- status: ok | 运行 0d 16h 50m | rss 96MB

## pm2 进程

| 进程 | 状态 | restarts | 内存 | 运行时长 |
| --- | --- | --- | --- | --- |
| mud-game-test | online | 3731 | 99MB | 0d 4h 31m |
| mud-game | online | 3668 | 98MB | 0d 16h 50m |
| mud-web | online | 3579 | 96MB | 0d 16h 50m |

## 系统

- 内存: 449MB / 3911MB
- 磁盘: 13% 已用（85G 可用）
- 端口监听: 31300✔ 31301✔ 8088✔

## 今日日志（UTC 2026-08-22）

- warn: 0 | error: 0 | fatal: 0

## 最近部署（deploy.log 末尾 20 行）

```
[2026-08-22 02:15:07] 前端构建完成 da466dd（www/ 已更新）

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
www/assets/index-S8NWkZZ9.css                           21.02 kB │ gzip:   4.93 kB
www/assets/index-C1Nv-MwH.js                           355.21 kB │ gzip: 100.10 kB

✓ built in 402ms
[2026-08-22 02:20:07] 前端构建完成 da466dd（www/ 已更新）
```
