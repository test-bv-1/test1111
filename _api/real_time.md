---
title: 实时成交
position_number: 1.5
type:
description:
parameters:
  - name:
    content:
content_markdown: |-
  * **URL**：/market/open/api/v1/platform/usdt/realTime?symbol=EOS/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: |-
      {
        "code": 1,
        "data": [
          {
            "size": "1",//数量
            "price": "1.999",//价格
            "side": 2,//方向 1:买 2:卖
            "time": 1650274754613,//是将
            "symbol": "EOS/USDT"
          },
          {
            "size": 1,
            "price": 2.55,
            "side": 1,
            "time": 1650274751574,
            "symbol": "EOS/USDT"
          },
          {
            "size": 1,
            "price": 2.55,
            "side": 1,
            "time": 1650274719644,
            "symbol": "EOS/USDT"
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
