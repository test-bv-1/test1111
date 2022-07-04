---
title: 24小时行情
position_number: 6
parameters:
  - name:
    content:
content_markdown:
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"TICKER\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"MARKET\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
right_code_blocks:
  - code_block: "{\n\t\"symbol\": \"BTC/USDT\",\n\t\"type\": \"TICKER\",\n\t\"data\": {\n\t\t\"amount\": \"12041429.0669052\",//成交量\n\t\t\"change\": \"3.62\",//涨跌幅\n\t\t\"high\": \"41258.86\",//高\n\t\t\"last\": \"40680.6\",//最新价\n\t\t\"low\": \"38538.02\",//低\n\t\t\"open\": \"38821.7\",//开盘价\n\t\t\"time\": \"1650347625464\",\n\t\t\"volume\": \"301.7915\"//成交数\n\t},\n\t\"ts\": 1650347625841\n}"
    title: 返回数据
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"TICKER\",\n\t\t\"symbol\": \"BTC/USDT\"\n\t}\n}"
    title: 响应
    language: json
---

