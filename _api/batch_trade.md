---
title: 24小时行情(批量)
position_number: 3.1
type:
description:
parameters:
  - name: limit
    content: Limit the number of books returned
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/ticker/list
  * **Method**：POST

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbolArray | String\[\] | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n\t\"symbolArray\": [\"BTC/USDT\",\"EOS/USDT\"]\r\n}"
    title: 请求示例
    language: json
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": [\r\n    {\r\n      \"time\": \"1650269906549\",//时间\r\n      \"last\": \"38989\",//价格\r\n      \"change\": \"-3.56\",//涨跌幅\r\n      \"symbol\": \"BTC/USDT\"//币对\r\n    },\r\n    {\r\n      \"time\": \"1650274754627\",\r\n      \"last\": \"1.999\",\r\n      \"change\": \"-21.61\",\r\n      \"symbol\": \"EOS/USDT\"\r\n    }\r\n  ],\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
