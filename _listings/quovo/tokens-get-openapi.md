---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 0
info:
  title: Quovo Get all active access tokens
  description: Retrieves all of your current Access Tokens.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tokens:
    get:
      summary: Get all active access tokens
      description: Retrieves all of your current Access Tokens.
      operationId: TokensGet
      x-api-path-slug: tokens-get
      responses:
        200:
          description: OK
      tags:
      - Active
      - Access
      - Tokens
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---