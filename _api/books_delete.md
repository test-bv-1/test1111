---
title: 实时成交
position_number: 1.5
type:
description:
parameters:
  - name:
    content:
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/realTime?symbol=EOS/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": [\r\n    {\r\n      \"size\": 1,//数量\r\n      \"price\": 1.999,//价格\r\n      \"side\": 2,//方向 1:买 2:卖\r\n      \"time\": 1650274754613,//是将\r\n      \"symbol\": \"EOS/USDT\"\r\n    },\r\n    {\r\n      \"size\": 1,\r\n      \"price\": 2.55,\r\n      \"side\": 1,\r\n      \"time\": 1650274751574,\r\n      \"symbol\": \"EOS/USDT\"\r\n    },\r\n    {\r\n      \"size\": 1,\r\n      \"price\": 2.55,\r\n      \"side\": 1,\r\n      \"time\": 1650274719644,\r\n      \"symbol\": \"EOS/USDT\"\r\n    }\r\n  ],\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
