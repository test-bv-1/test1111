---
title: K线
position_number: 7
parameters:
  - name:
    content:
content_markdown: |-
  periods:k线类型

  "1min":0

  "5min": 2

  "15min":3

  "30min":4

  "1hour":5

  "4hour":7

  "1day":10

  "1week":11

  "1month":12

  "1year":13

  多个k线类型逗号分隔
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"KLINE\",\n\t\"symbol\": \"BTC/USDT\",\n\t\"params\": {\n\t\t\"periods\": \"0,2\"\n\t}\n}\n"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"KLINE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
right_code_blocks:
  - code_block: "{\n\t\"symbol\": \"BTC/USDT\",\n\t\"type\": \"KLINE\",\n\t\"data\": [{\n\t\t\"open\": \"40716.4\",\n\t\t\"high\": \"40716.6\",\n\t\t\"low\": \"40702.8\",\n\t\t\"close\": \"40702.8\",\n\t\t\"volume\": \"0.00735\",\n\t\t\"amount\": \"299.24742\",\n\t\t\"type\": 0,\n\t\t\"time\": 1650352200000\n\t}],\n\t\"ts\": 1650352218714\n}"
    title: 返回数据
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"KLINE\",\n\t\t\"params\": {\n\t\t\t\"periods\": \"0,2\"\n\t\t},\n\t\t\"symbol\": \"BTC/USDT\"\n\t}\n}"
    title: 响应
    language: json
---
