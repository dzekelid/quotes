---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Historical Get Historical Quotes As Of Adjusted
  description: This operation returns a range of quotes for a security. This includes
    split and dividends adjusted price.
  version: 1.0.0
host: www.xignite.com
basePath: xHistorical.json/XigniteHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetHistoricalQuotesAdjusted:
    get:
      summary: Get Historical Quotes Adjusted
      description: Returns a quote as of a historical date. This includes split and
        dividends adjusted price.
      operationId: postGethistoricalquotesadjusted
      x-api-path-slug: gethistoricalquotesadjusted-get
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
      - Historical
      - Quotes
      - Adjusted
  /GetHistoricalMonthlyQuotesRangeAdjusted:
    get:
      summary: Get Historical Monthly Quotes Range Adjusted
      description: This operation returns end of month quotes for a US equity. This
        includes split and dividends adjusted price.
      operationId: postGethistoricalmonthlyquotesrangeadjusted
      x-api-path-slug: gethistoricalmonthlyquotesrangeadjusted-get
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
      - Historical
      - Monthly
      - Quotes
      - Range
      - Adjusted
  /GetHistoricalQuotesAsOfAdjusted:
    get:
      summary: Get Historical Quotes As Of Adjusted
      description: This operation returns a range of quotes for a security. This includes
        split and dividends adjusted price.
      operationId: postGethistoricalquotesasofadjusted
      x-api-path-slug: gethistoricalquotesasofadjusted-get
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
      - Historical
      - Quotes
      - As
      - Adjusted
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