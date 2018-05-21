---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite NASDAQ Last Sale Get Extended Quotes
  description: Returns real-time NASDAQ BASIC quotes for given securities.
  version: 1.0.0
host: nasdaqlastsale.xignite.com
basePath: xNASDAQLastSale.json/XigniteNASDAQLastSale
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetQuotes:
    post:
      summary: Get Quotes
      description: Returns real-time NASDAQ BASIC quotes for given securities.
      operationId: GetQuotes
      x-api-path-slug: getquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Quotes
  /GetExtendedQuotes:
    post:
      summary: Get Extended Quotes
      description: Returns real-time NASDAQ BASIC quotes for given securities.
      operationId: GetExtendedQuotes
      x-api-path-slug: getextendedquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
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