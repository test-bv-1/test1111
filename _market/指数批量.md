---
title: 指数(批量)
position_number: 4
parameters:
  - name:
    content:
content_markdown:
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"INDEX_PRICE_ALL\",\n\t\"symbols\": \"BTC/USDT,ETH/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"INDEX_PRICE_ALL\"\n}"
    title: 取消订阅
    language: json
right_code_blocks:
  - code_block: "{\n\t\"type\": \"INDEX_PRICE_ALL\",\n\t\"data\": [{\n\t\t\"symbol\": \"BTC/USDT\",\n\t\t\"price\": \"20547.103000000\"\n\t}, {\n\t\t\"symbol\": \"ETH/USDT\",\n\t\t\"price\": \"1095.646000000\"\n\t}],\n\t\"ts\": 1655971790464\n}"
    title: 返回数据
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"INDEX_PRICE_ALL\",\n\t\t\"symbols\": \"BTC/USDT,ETH/USDT\"\n\t}\n}"
    title: 响应
    language: json
---

