---
title: 深度
position_number: 5
parameters:
  - name:
    content:
content_markdown:
left_code_blocks:
  - code_block: "{\n\t\"event\": \"SUB\",\n\t\"type\": \"DEPTH\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 请求订阅
    language: json
  - code_block: "{\n\t\"event\": \"UNSUB\",\n\t\"type\": \"DEPTH\",\n\t\"symbol\": \"BTC/USDT\"\n}"
    title: 取消订阅
    language: json
right_code_blocks:
  - code_block: "{\n\t\"symbol\": \"BTC/USDT\",\n\t\"type\": \"DEPTH\",\n\t\"data\": {\n\t\t\"asks\": [//asks （升序）卖 下标0价格，1数量\n\t\t\t[\"40592\", \"1.33301\"],\n\t\t\t[\"40593\", \"1.02589\"],\n\t\t\t[\"40594\", \"0.17704\"],\n\t\t\t[\"40595\", \"0.1593\"],\n\t\t\t[\"40596\", \"1.15614\"]\n\t\t],\n\t\t\"bids\": [//bids （降序）买\n\t\t\t[\"40497\", \"0.62148\"],\n\t\t\t[\"40498\", \"0.47407\"],\n\t\t\t[\"40499\", \"1.05067\"],\n\t\t\t[\"40500\", \"0.26455\"],\n\t\t\t[\"40501\", \"0.78471\"],\n\t\t\t[\"40502\", \"0.44409\"],\n\t\t]\n\t},\n\t\"ts\": 1650352632920\n}"
    title: 返回数据
    language: json
  - code_block: "{\n\t\"code\": 1,\n\t\"desc\": \"success\",\n\t\"topic\": {\n\t\t\"event\": \"SUB\",\n\t\t\"type\": \"DEPTH\",\n\t\t\"symbol\": \"BTC/USDT\"\n\t}\n}"
    title: 响应
    language: json
---

asks （升序）卖

bids （降序）买

&nbsp;

\["7051","47231"\]

价格 数量
