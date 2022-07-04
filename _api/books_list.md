---
title: 指数价格
position_number: 3
type: get
description:
parameters:
  - name: limit
    content: Limit the number of books returned
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/index?symbol=ETH/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": {\r\n    \"symbol\": \"ETH/USDT\",//币对\r\n    \"indexPrice\": 2902.912//指数价格\r\n  },\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
