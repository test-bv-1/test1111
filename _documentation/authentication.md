---
title: Authentication
position_number: 2
parameters:
  - name:
    content:
content_markdown: |-
  You need to be authenticated for all API requests. You can generate an API key in your developer dashboard.

  Add the API key to all requests as a GET parameter.

  Nothing will work unless you include this API key

right_code_blocks:
  - code_block: |-
      {
        "error": true,
        "message": "Book doesn't exist"
      }
    title: Response
    language: json
---
