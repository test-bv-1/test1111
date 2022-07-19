---
title: 指数价格(批量)
position_number: 1.1
type:
description:
parameters:
  - name:
    content:
content_markdown: |-
  * **URL**：/market/open/api/v1/platform/swaps/index/list
  * **Method**：POST

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbolArray | String\[\] | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n\t\"symbolArray\": [\"BTC/USDT\",\"EOS/USDT\"]\r\n}"
    title: 请求示例
    language: json
  - code_block: |-
      {
        "code": 1,
        "data": [
          {
            "symbol": "BTC/USDT",
            "indexPrice": "40781.23"
          },
          {
            "symbol": "EOS/USDT",
            "indexPrice": "2.445"
          }
        ],
        "message": "SUCCESS"
      }
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
