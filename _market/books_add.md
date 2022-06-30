---
title: test
position_number: 1.1
type:
description: Create Book
parameters:
  - name: title
    content: The title for the book
  - name: score
    content: The book's score between 0 and 5
content_markdown: >-
  \| 通知类型消息(前置条件登录) \| \| \|


  \| --- \| --- \| --- \|


  \| 请求 \| \{"event":"SUB","type":"ORDER", "businessType":"USDT"\} \| \|


  \| 订阅回执 \| \{"code":1,"desc":"success","type":"ORDER"\} \| \|


  \| 增量返回 \|
  \{"type":"ORDER","businessType":"USDT","userId":1,"data":\{"currencyPairId":1001,"orderType":1,"price":"1000","quantity":"200","leverage":"100","side":1,"positionSide":1,"operationType":101\}\}
  \| currencyPairId：币对id&lt;br /&gt;orderType：类型 1-限价 2-市价&lt;br
  /&gt;price：价格&lt;br /&gt;quantity：数量&lt;br /&gt;leverage：杠杆&lt;br /&gt;side：
  买卖方向,1:买,2:卖&lt;br /&gt;positionSide：持仓方向,1:多,2:空&lt;br
  /&gt;operationType：操作类型，101：成交，102：委托 \|
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

mknjknkjnkjnjknkj
