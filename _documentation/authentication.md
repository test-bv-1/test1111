---
title: 行情
position_number: 2
parameters:
  - name:
    content:
content_markdown: |-
  心跳规则：2s一次<br />{"event":"ping"}<br />{"event":"pong"}
    
    
  | 公用code码 （type字段为订阅的业务类型） |  |
  | --- | --- |
  | 成功订阅 | {"code":1,"desc":"success","type":"MARKET"}   |
  | 重复订阅 | {"code":10001,"desc":"重复订阅","type":"MARKET"} |
  | 参数异常 | {"code":10000,"desc":"参数异常","type":"MARKET"} |

right_code_blocks:
  - code_block: |-
      {
        "error": true,
        "message": "Book doesn't exist"
      }
    title: Response
    language: json
---
