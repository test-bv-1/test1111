---
title: 实时成交
position_number: 7
parameters:
  - name:
    content:
content_markdown:
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"TRADE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"TRADE\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
right_code_blocks:
  - code_block: "{\n\t\"symbol\": \"BTC/USDT\",\n\t\"type\": \"TRADE\",\n\t\"data\": [{\n\t\t\"size\": \"0.0003\",//数量\n\t\t\"price\": \"40711.4\",//价格\n\t\t\"side\": 1,//方向 1:买 2：卖\n\t\t\"time\": 1650352384250\n\t}],\n\t\"ts\": 1650352384312\n}"
    title: 返回数据
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"TRADE\",\n\t\t\"symbol\": \"BTC/USDT\"\n\t}\n}"
    title: 响应
    language: json
---

