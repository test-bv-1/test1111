---
title: 指数
position_number: 3
parameters:
  - name:
    content:
content_markdown:
right_code_blocks:
  - code_block: >-
      {"code":1,"desc":"success","topic":{"event":"SUB","type":"INDEX_PRICE_ALL","symbols":"BTC/USDT,ETH/USDT"}}
    title: 订阅回执
    language: json
  - code_block: |-
      {
        "symbol": "BTC/USDT",
        "type": "INDEX_PRICE",
        "data": "40658.981000000",
        "ts": 1650352557873
      }
    title: 增量回执
    language: json
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
---

