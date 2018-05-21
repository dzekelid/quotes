---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite BATS Real Time Get Real Quotes
  description: Returns a collection of real time stock quotes for a comma-separated
    list of stock quotes.
  version: 1.0.0
host: batsrealtime.xignite.com
basePath: xBATSRealTime.json/XigniteBATSRealTime
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetRealQuotes:
    post:
      summary: Get Real Quotes
      description: Returns a collection of real time stock quotes for a comma-separated
        list of stock quotes.
      operationId: GetRealQuotes
      x-api-path-slug: getrealquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Real
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