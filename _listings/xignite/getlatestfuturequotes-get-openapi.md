---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Real Time Futures Get Latest Future Quotes
  description: Returns latest realtime quotes for multiple future contracts.
  version: 1.0.0
host: globalrealtimefutures.xignite.com
basePath: xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetFutureQuotes:
    get:
      summary: Get Future Quotes
      description: Returns realtime quotes for multiple future contracts.
      operationId: GetFutureQuotes
      x-api-path-slug: getfuturequotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Future
      - Quotes
  /GetLatestFutureQuotes:
    get:
      summary: Get Latest Future Quotes
      description: Returns latest realtime quotes for multiple future contracts.
      operationId: GetLatestFutureQuotes
      x-api-path-slug: getlatestfuturequotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Future
      - Quotes
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