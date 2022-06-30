---
title: test
position_number: 1.1
type:
description:
content_markdown: >-
  Websocket 行情推送


  * 本篇所列出的所有wss接口，共有如下两种连接方式：
    * 连接方式一：
    * Base Url：**wss://fstream.binance.com**
    * 订阅单一stream格式为&nbsp;**/ws/&lt;streamName&gt;**
    * 组合streams的URL格式为&nbsp;**/stream?streams=&lt;streamName1&gt;/&lt;streamName2&gt;/&lt;streamName3&gt;**
    * 连接样例：
    * wss://fstream.binance.com/ws/bnbusdt@aggTrade
    * wss://fstream.binance.com/stream?streams=bnbusdt@aggTrade/btcusdt@markPrice
    * 连接方式二：
    * Base Url：**wss://fstream-auth.binance.com**
    * 订阅单一stream格式为&nbsp;**/ws/&lt;streamName&gt;?listenKey=&lt;validateListenKey&gt;**
    * 组合streams的URL格式为&nbsp;**/stream?streams=&lt;streamName1&gt;/&lt;streamName2&gt;/&lt;streamName3&gt;&listenKey=&lt;validateListenKey&gt;**
    * **&lt;validateListenKey&gt;在建立连接时，必须为一个有效的listenKey**
    * 连接样例：
    * wss://fstream-auth.binance.com/ws/btcusdt@markPrice?listenKey=XaEAKTsQSRLZAGH9tuIu37plSRsdjmlAVBoNYPUITlTAko1WI22PgmBMpI1rS8Yh
    * wss://fstream-auth.binance.com/stream?streams=btcusdt@markPrice@1s/bnbusdt@markPrice&listenKey=XaEAKTsQSRLZAGH9tuIu37plSRsdjmlAVBoNYPUITlTAko1WI22PgmBMpI1rS8Yh
  *
  订阅组合streams时，事件payload会以这样的格式封装&nbsp;**\{"stream":"&lt;streamName&gt;","data":&lt;rawPayload&gt;\}**
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

