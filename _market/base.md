---
title: 基本信息
position_number: 1.1
type:
description:
content_markdown: |-
  &nbsp;

  * 连接方式如下：
    * Base Url：**wss://xxx.com/**
    * URL格式为&nbsp;**/usdt**
right_code_blocks:
  - code_block: |-
      {
        "id": 3,
        "title": "The Book Thief",
        "score": 4.3,
        "dateAdded": "5/1/2015"
      }
    title: Response
    language: json
---

* 连接方式如下：
  * Base Url：**wss://xxx.com/**
  * URL格式为&nbsp;**/usdt**

* 心跳规则：
  * 心跳次数/10s
  * 客户端发送：\{"event":"ping"\}
  * 服务端回执：\{"event":"pong"\}
