---
title: K线
position_number: 2
type:
description:
parameters:
  - name: title
    content: The title for the book
content_markdown: >-
  * **URL**：/open/market/api/v1/platform/usdt/kline

  * **Method**：GET


  请求参数


  | 参数 | 类型 | 是否必填 | 描述 |

  | symbol | String | true | 币对 |

  | type | Integer | true | 周期类型 :0 :1min ,2:5min ,3:15min ,4:30min 5:1hour
  ,7:4hour ,10:1day ,11 :1week,12:1month, 13:1year\:1week,12:1month, 13:1year |

  | since | Long | true | k线开始时间戳精确到分钟(1650016682000) |

  | end | Long | true | k线结束时间戳精确到分钟 |
right_code_blocks:
  - code_block: "{\r\n  \"code\": 1,\r\n  \"data\": [\r\n    {\r\n      \"open\": 40373.2,//开盘价\r\n      \"high\": 40391.82,//最高价\r\n      \"low\": 40372.84,//最低价格\r\n      \"close\": 40391.72,//收盘价格\r\n      \"volume\": 0.0522,//成交数\r\n      \"amount\": 2107.840752,//成交额\r\n      \"type\": 0,//周期类型\r\n      \"time\": 1650096180000,//时间\r\n      \"symbol\": \"BTC/USDT\"//币对\r\n    },\r\n    {\r\n      \"open\": 40391.74,\r\n      \"high\": 40391.74,\r\n      \"low\": 40387.62,\r\n      \"close\": 40388.52,\r\n      \"volume\": 0.0568,\r\n      \"amount\": 2294.074692,\r\n      \"type\": 0,\r\n      \"time\": 1650096240000,\r\n      \"symbol\": \"BTC/USDT\"\r\n    }\r\n  ]\r\n  \"message\": \"SUCCESS\"\r\n}"
    title: 响应
    language: json
  - code_block: "{\r\n  \"code\": 0,\r\n  \"data\": null,\r\n  \"message\": \"FAILURE\"\r\n}"
    title: Error
    language: json
---
