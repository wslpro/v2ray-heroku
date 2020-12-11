# Heroku soso

## 概述

用于在 Heroku 上部署 Websocket。

**可以部署两个以上的应用，实现 [负载均衡](https://toutyrater.github.io/app/balance.html)，避免长时间大流量连接某一应用而判定为滥用。**

## 部署
![Deploy](https://www.herokucdn.com/deploy/button.png)
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/wslpro/v2ray-heroku)

## ENV 设定

### UUID

`UUID` > `一个 UUID，供用户连接时验证身份使用`。

## Info

WebSocket Path: `/`
alterId: `64`

V2Ray 将在部署时自动安装最新版本。

**出于安全考量，请不要使用自定义域名，使用 Heroku 分配的二级域名**
