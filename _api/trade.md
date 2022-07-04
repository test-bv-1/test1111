---
title: 最新价格
position_number: 4
type:
description:
parameters:
  - name: title
    content: The title for the book
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/ticker/last?symbol=EOS/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": {\r\n    \"time\": \"1650274754627\",//时间\r\n    \"last\": \"1.999\",//价格\r\n    \"symbol\": \"EOS/USDT\"\r\n  },\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
