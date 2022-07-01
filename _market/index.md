---
title: 指数
position_number: 3
parameters:
  - name:
    content:
content_markdown:
right_code_blocks:
  - code_block: |-
      {
        "symbol": "BTC/USDT",
        "type": "INDEX_PRICE",
        "data": "40658.981000000",
        "ts": 1650352557873
      }
    title: 增量回执
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"INDEX_PRICE_ALL\",\n\t\t\"symbols\": \"BTC/USDT,ETH/USDT\"\n\t}\n}"
    title: 订阅回执
    language: json
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"INDEX_PRICE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
---

