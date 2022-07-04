---
title: 24小时行情
position_number: 3
type:
description:
parameters:
  - name: limit
    content: Limit the number of books returned
content_markdown: |-
  * **URL**：/open/market/api/v1/platform/usdt/ticker?symbol=BTC/USDT
  * **Method**：GET

  请求参数

  | 参数 | 类型 | 是否必填 | 描述 |
  | symbol | String | true | 币对 |
left_code_blocks:
  - code_block: curl http://sampleapi.readme.com/orders?key=YOUR_APP_KEY
    title: Curl
    language: bash
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": {\r\n    \"time\": \"1650278049804\",//时间\r\n    \"last\": \"39056.18\",//价格\r\n    \"change\": \"-3.43\",//涨跌幅\r\n    \"symbol\": \"BTC/USDT\",//币对\r\n    \"open\": \"40421.94\",//开盘价格\r\n    \"high\": \"40593.22\",//24小时最高价格\r\n    \"low\": \"38538.02\",//24小时最低价格\r\n    \"volume\": \"182.40568\",//成交量\r\n    \"amount\": \"7223419.4784845\"//成交金额\r\n  },\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
