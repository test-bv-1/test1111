---
title: 基本信息
position_number: 1.1
type:
description:
content_markdown: |-
  * 连接方式如下：
    * Base Url：**wss://xxx.com/**
    * URL格式为 **/usdt**
  * 心跳规则：
    * 心跳次数/30s
    * 客户端发送：\{"event":"ping"\}
    * 服务端回执：\{"event":"pong"\}

      | 公用code码 （type字段为订阅类型） |  |
      | --- | --- |
      | 成功订阅 | \{"code":1,"desc":"success","type":"MARKET"\} |
      | 事件类型不存在 | \{"code":10001,"desc":"不存在的事件类型","type":"MARKET"\} |
      | 请求json格式错误 | \{"code":10000,"desc":"json格式错误","type":"MARKET"\} |
---

