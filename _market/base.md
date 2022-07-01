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
    * 心跳次数/10s
    * 客户端发送：**\{"event":"ping"\}**
    * 服务端回执：**\{"event":"pong"\}**
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
---

* 连接方式如下：
  * Base Url：**wss://xxx.com/**
  * URL格式为 **/usdt**
* 心跳规则：
  * 心跳次数/30s
  * 客户端发送：\{"event":"ping"\}
  * 服务端回执：\{"event":"pong"\}
