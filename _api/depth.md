---
title: 深度
position_number: 1.3
type:
description:
parameters:
  - name:
    content:
content_markdown: |-
  * **URL**：/market/open/api/v1/platform/usdt/depth?symbol=EOS/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": {\r\n    \"symbol\": \"EOS/USDT\",//币对\r\n    \"bids\": [ //买单\r\n      [\r\n        \"1.999\",//价格\r\n        \"9592\"//数量\r\n      ]\r\n    ],\r\n    \"asks\": [//卖单\r\n      [\r\n        \"2.6\",\r\n        \"1\"\r\n      ],\r\n      [\r\n        \"2.55\",\r\n        \"4840\"\r\n      ]\r\n      \r\n    ]\r\n  },\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
