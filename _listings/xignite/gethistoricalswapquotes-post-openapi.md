---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Futures Get Historical Swap Quotes
  description: Returns historical swap quotes within a date range
  version: 1.0.0
host: globalfutures.xignite.com
basePath: xGlobalFutures.json/XigniteGlobalFutures
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetFutureQuotes:
    post:
      summary: Get Future Quotes
      description: Returns delayed quotes for multiple future contracts.
      operationId: GetFutureQuotes
      x-api-path-slug: getfuturequotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Future
      - Quotes
  /GetLatestFutureQuotes:
    post:
      summary: Get Latest Future Quotes
      description: Returns latest delayed quotes for multiple future contracts.
      operationId: GetLatestFutureQuotes
      x-api-path-slug: getlatestfuturequotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Future
      - Quotes
  /GetLatestFrontMonthFutureQuotes:
    post:
      summary: Get Latest Front Month Future Quotes
      description: Returns latest quotes for front month futures
      operationId: GetLatestFrontMonthFutureQuotes
      x-api-path-slug: getlatestfrontmonthfuturequotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Front
      - Month
      - Future
      - Quotes
  /GetAllFutureQuotes:
    post:
      summary: Get All Future Quotes
      description: Returns all delayed future quotes for a future base.
      operationId: GetAllFutureQuotes
      x-api-path-slug: getallfuturequotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Future
      - Quotes
  /GetAllOptionQuotes:
    post:
      summary: Get All Option Quotes
      description: Returns all delayed future option quotes for a future contract.
      operationId: GetAllOptionQuotes
      x-api-path-slug: getalloptionquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Option
      - Quotes
  /GetFutureOptionQuotes:
    post:
      summary: Get Future Option Quotes
      description: Returns delayed future option quotes for multiple future options.
      operationId: GetFutureOptionQuotes
      x-api-path-slug: getfutureoptionquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Future
      - Option
      - Quotes
  /GetLatestFutureOptionQuotes:
    post:
      summary: Get Latest Future Option Quotes
      description: Returns latest delayed quotes for multiple future options.
      operationId: GetLatestFutureOptionQuotes
      x-api-path-slug: getlatestfutureoptionquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Future
      - Option
      - Quotes
  /GetHistoricalSwapQuotes:
    post:
      summary: Get Historical Swap Quotes
      description: Returns historical swap quotes within a date range
      operationId: GetHistoricalSwapQuotes
      x-api-path-slug: gethistoricalswapquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Swap
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