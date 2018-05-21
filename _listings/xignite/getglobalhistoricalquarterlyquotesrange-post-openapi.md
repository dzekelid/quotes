---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Historical Get Global Historical Quarterly Quotes Range
  description: Returns a range of quarterly Global Historical quotes for a security.
    For more information, go to http://www.xignite.com/
  version: 1.0.0
host: www.xignite.com
basePath: xGlobalHistorical.json/XigniteGlobalHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetEndOfDayQuotes:
    post:
      summary: Get End Of Day Quotes
      description: Returns a quote as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetendofdayquotes
      x-api-path-slug: getendofdayquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - End
      - Of
      - Day
      - Quotes
  /GetEndOfDayQuotesRange:
    post:
      summary: Get End Of Day Quotes Range
      description: Returns a quote a complete range of stock quotes for a given equity.
        This includes the adjusted price as specified.
      operationId: postGetendofdayquotesrange
      x-api-path-slug: getendofdayquotesrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - End
      - Of
      - Day
      - Quotes
      - Range
  /GetGlobalHistoricalQuotes:
    post:
      summary: Get Global Historical Quotes
      description: Returns quotes as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetglobalhistoricalquotes
      x-api-path-slug: getglobalhistoricalquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Quotes
  /GetGlobalHistoricalQuotesAsOf:
    post:
      summary: Get Global Historical Quotes As Of
      description: This operation returns a range of quotes for a security.
      operationId: postGetglobalhistoricalquotesasof
      x-api-path-slug: getglobalhistoricalquotesasof-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Quotes
      - As
      - Of
  /GetGlobalHistoricalQuotesRange:
    post:
      summary: Get Global Historical Quotes Range
      description: This operation returns a complete range of stock quotes for a given
        equity. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalquotesrange
      x-api-path-slug: getglobalhistoricalquotesrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Quotes
      - Range
  /GetGlobalHistoricalQuotesRangeExtended:
    post:
      summary: Get Global Historical Quotes Range Extended
      description: This operation returns a complete range of global historical quotes
        extended for a given equity. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalquotesrangeextended
      x-api-path-slug: getglobalhistoricalquotesrangeextended-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Quotes
      - Range
      - Extended
  /GetGlobalHistoricalWeeklyQuotesRange:
    post:
      summary: Get Global Historical Weekly Quotes Range
      description: Returns a range of weekly Global Historical quotes for a security.
        For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalweeklyquotesrange
      x-api-path-slug: getglobalhistoricalweeklyquotesrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Weekly
      - Quotes
      - Range
  /GetGlobalHistoricalWeeklyQuotesRangeExtended:
    post:
      summary: Get Global Historical Weekly Quotes Range Extended
      description: Returns a range of weekly Global Historical quotes extended for
        a security. For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalweeklyquotesrangeextended
      x-api-path-slug: getglobalhistoricalweeklyquotesrangeextended-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Weekly
      - Quotes
      - Range
      - Extended
  /GetGlobalHistoricalQuarterlyQuotesRange:
    post:
      summary: Get Global Historical Quarterly Quotes Range
      description: Returns a range of quarterly Global Historical quotes for a security.
        For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalquarterlyquotesrange
      x-api-path-slug: getglobalhistoricalquarterlyquotesrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global
      - Historical
      - Quarterly
      - Quotes
      - Range
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