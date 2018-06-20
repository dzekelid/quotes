---
swagger: "2.0"
x-collection-name: Barchart
x-complete: 0
info:
  title: Barchart API Get Quote
  description: The getQuote API is used to request price data, either real-time, delayed
    or end-of-day, by symbol. In addition to Last Price or Settlement, other fields
    such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available.
  version: 1.0.0
host: marketdata.websol.barchart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /getQuote.json:
    get:
      summary: Get Quote
      description: The getQuote API is used to request price data, either real-time,
        delayed or end-of-day, by symbol. In addition to Last Price or Settlement,
        other fields such as Open, High, Low, Close, Bid, Ask, 52-week high and low,
        and more are available.
      operationId: getQuote
      x-api-path-slug: getquote-json-get
      parameters:
      - in: query
        name: symbols
        description: A symbol or code that identifies a financial instrument
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
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