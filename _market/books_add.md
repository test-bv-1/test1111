---
title: 基本信息
position_number: 1.1
type:
description:
content_markdown: |-
  &nbsp;

  * 本篇所列出的所有wss接口，有如下连接方式：
    * 连接方式：
    * Base Url：**wss://xxx.com/**
    * URL格式为&nbsp;**/usdt**
left_code_blocks:
  - code_block: |-
      $.post("http://api.myapp.com/books/", {
        "token": "YOUR_APP_KEY",
        "title": "The Book Thief",
        "score": 4.3
      }, function(data) {
        alert(data);
      });
    title: jQuery
    language: javascript
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

Websocket 行情推送

* 本篇所列出的所有wss接口，有如下连接方式：
  * 连接方式：
  * Base Url：**wss://xxx.com/**
  * URL格式为&nbsp;**/usdt**
