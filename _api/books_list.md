---
title: 指数价格
position_number: 1
type:
description:
parameters:
  - name:
    content:
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/index?symbol=ETH/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: |-
      {
        "code": 1,
        "data": {
          "symbol": "ETH/USDT",//币对
          "indexPrice": "2902.912"//指数价格
        },
        "message": "SUCCESS"
      }
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---