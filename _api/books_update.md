---
title: 批量获取指数价格
position_number: 1.4
type: post
description:
parameters:
  - name: title
    content: The title for the book
  - name: score
    content: The book's score between 0 and 5
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/swaps/index/list
  * **Method**：POST

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbolArray | String\[\] | true | 币对 |
left_code_blocks:
  - code_block: |-
      $.ajax({
        "url": "http://api.myapp.com/books/3",
        "type": "PUT",
        "data": {
          "token": "YOUR_APP_KEY",
          "score": 5.0,
          "title": "The Book Stealer"
        },
        "success": function(data) {
          alert(data);
        }
      });
    title: jQuery
    language: javascript
right_code_blocks:
  - code_block: "{\r\n\t\"symbolArray\": [\"BTC/USDT\",\"EOS/USDT\"]\r\n}"
    title: 请求示例
    language: json
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": [\r\n    {\r\n      \"symbol\": \"BTC/USDT\",\r\n      \"indexPrice\": 40781.23\r\n    },\r\n    {\r\n      \"symbol\": \"EOS/USDT\",\r\n      \"indexPrice\": 2.445\r\n    }\r\n  ],\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---