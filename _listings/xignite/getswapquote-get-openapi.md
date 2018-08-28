---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Real Time Futures Get Swap Quote
  description: Returns realtime quote for a swap
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
  /GetRealQuotes:
    get:
      summary: Get Real Quotes
      description: Returns a collection of real time stock quotes for a comma-separated
        list of stock quotes.
      operationId: GetRealQuotes
      x-api-path-slug: getrealquotes-get
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
      - Real
      - Quotes
  /GetRealQuotesByIdentifiers:
    get:
      summary: Get Real Quotes By Identifiers
      description: Returns a collection of real time stock quotes for a comma-separated
        list of stock quotes.
      operationId: GetRealQuotesByIdentifiers
      x-api-path-slug: getrealquotesbyidentifiers-get
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
      - Real
      - Quotes
      - Identifiers
  /GetRealQuote:
    get:
      summary: Get Real Quote
      description: Returns real time stock quote for a given stock ticker
      operationId: GetRealQuote
      x-api-path-slug: getrealquote-get
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
      - Real
      - Quote
  /GetRealQuoteByIdentifier:
    get:
      summary: Get Real Quote By Identifier
      description: Returns a real-time quote for a security based on the last trade
        execution.
      operationId: GetRealQuoteByIdentifier
      x-api-path-slug: getrealquotebyidentifier-get
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
      - Real
      - Quote
      - Identifier
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
  /GetLatestFrontMonthFutureQuotes:
    get:
      summary: Get Latest Front Month Future Quotes
      description: Returns latest quotes for front month futures
      operationId: GetLatestFrontMonthFutureQuotes
      x-api-path-slug: getlatestfrontmonthfuturequotes-get
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
      - Front
      - Month
      - Future
      - Quotes
  /GetAllFutureQuotes:
    get:
      summary: Get All Future Quotes
      description: Returns all delayed future quotes for a future base.
      operationId: GetAllFutureQuotes
      x-api-path-slug: getallfuturequotes-get
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
  /GetAllOptionQuotes:
    get:
      summary: Get All Option Quotes
      description: Returns all realtime future option quotes for a future contract.
      operationId: GetAllOptionQuotes
      x-api-path-slug: getalloptionquotes-get
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
      - Option
      - Quotes
  /GetFutureOptionQuotes:
    get:
      summary: Get Future Option Quotes
      description: Returns realtime future option quotes for multiple future options.
      operationId: GetFutureOptionQuotes
      x-api-path-slug: getfutureoptionquotes-get
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
      - Option
      - Quotes
  /GetLatestFutureOptionQuotes:
    get:
      summary: Get Latest Future Option Quotes
      description: Returns latest realtime quotes for multiple future options.
      operationId: GetLatestFutureOptionQuotes
      x-api-path-slug: getlatestfutureoptionquotes-get
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
      - Option
      - Quotes
  /GetHistoricalSwapQuotes:
    get:
      summary: Get Historical Swap Quotes
      description: Returns historical swap quotes within a date range
      operationId: GetHistoricalSwapQuotes
      x-api-path-slug: gethistoricalswapquotes-get
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
  /GetHistoricalFutureQuotesRange:
    get:
      summary: Get Historical Future Quotes Range
      description: Returns historical future quotes on a future contract within a
        date range
      operationId: GetHistoricalFutureQuotesRange
      x-api-path-slug: gethistoricalfuturequotesrange-get
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
      - Future
      - Quotes
      - Range
  /GetFutureQuote:
    get:
      summary: Get Future Quote
      description: Returns a realtime quote for a future contract.
      operationId: GetFutureQuote
      x-api-path-slug: getfuturequote-get
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
      - Quote
  /GetLatestFutureQuote:
    get:
      summary: Get Latest Future Quote
      description: Returns the latest realtime quote for a future contract.
      operationId: GetLatestFutureQuote
      x-api-path-slug: getlatestfuturequote-get
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
      - Quote
  /GetSpotFutureQuote:
    get:
      summary: Get Spot Future Quote
      description: Returns a realtime spot quote for a future contract.
      operationId: GetSpotFutureQuote
      x-api-path-slug: getspotfuturequote-get
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
      - Spot
      - Future
      - Quote
  /GetLMEFutureQuote:
    get:
      summary: Get LME Future Quote
      description: Returns latest quotes for LME futures
      operationId: GetLMEFutureQuote
      x-api-path-slug: getlmefuturequote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - LME
      - Future
      - Quote
  /GetFutureOptionQuote:
    get:
      summary: Get Future Option Quote
      description: Returns a realtime future option quote for a future option.
      operationId: GetFutureOptionQuote
      x-api-path-slug: getfutureoptionquote-get
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
      - Option
      - Quote
  /GetLatestFutureOptionQuote:
    get:
      summary: Get Latest Future Option Quote
      description: Returns latest realtime quote for multiple future option.
      operationId: GetLatestFutureOptionQuote
      x-api-path-slug: getlatestfutureoptionquote-get
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
      - Option
      - Quote
  /GetSwapQuote:
    get:
      summary: Get Swap Quote
      description: Returns realtime quote for a swap
      operationId: GetSwapQuote
      x-api-path-slug: getswapquote-get
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
      - Swap
      - Quote
  /GetEndOfDayQuotes:
    get:
      summary: Get End Of Day Quotes
      description: Returns a quote as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetendofdayquotes
      x-api-path-slug: getendofdayquotes-get
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
      - End
      - Of
      - Day
      - Quotes
  /GetEndOfDayQuotesRange:
    get:
      summary: Get End Of Day Quotes Range
      description: Returns a quote a complete range of stock quotes for a given equity.
        This includes the adjusted price as specified.
      operationId: postGetendofdayquotesrange
      x-api-path-slug: getendofdayquotesrange-get
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
      - End
      - Of
      - Day
      - Quotes
      - Range
  /GetGlobalHistoricalQuotes:
    get:
      summary: Get Global Historical Quotes
      description: Returns quotes as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetglobalhistoricalquotes
      x-api-path-slug: getglobalhistoricalquotes-get
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
      - Global
      - Historical
      - Quotes
  /GetGlobalHistoricalQuotesAsOf:
    get:
      summary: Get Global Historical Quotes As Of
      description: This operation returns a range of quotes for a security.
      operationId: postGetglobalhistoricalquotesasof
      x-api-path-slug: getglobalhistoricalquotesasof-get
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
      - Global
      - Historical
      - Quotes
      - As
      - Of
  /GetGlobalHistoricalQuotesRange:
    get:
      summary: Get Global Historical Quotes Range
      description: This operation returns a complete range of stock quotes for a given
        equity. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalquotesrange
      x-api-path-slug: getglobalhistoricalquotesrange-get
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
      - Global
      - Historical
      - Quotes
      - Range
  /GetGlobalHistoricalQuotesRangeExtended:
    get:
      summary: Get Global Historical Quotes Range Extended
      description: This operation returns a complete range of global historical quotes
        extended for a given equity. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalquotesrangeextended
      x-api-path-slug: getglobalhistoricalquotesrangeextended-get
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
      - Global
      - Historical
      - Quotes
      - Range
      - Extended
  /GetGlobalHistoricalWeeklyQuotesRange:
    get:
      summary: Get Global Historical Weekly Quotes Range
      description: Returns a range of weekly Global Historical quotes for a security.
        For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalweeklyquotesrange
      x-api-path-slug: getglobalhistoricalweeklyquotesrange-get
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
      - Global
      - Historical
      - Weekly
      - Quotes
      - Range
  /GetGlobalHistoricalWeeklyQuotesRangeExtended:
    get:
      summary: Get Global Historical Weekly Quotes Range Extended
      description: Returns a range of weekly Global Historical quotes extended for
        a security. For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalweeklyquotesrangeextended
      x-api-path-slug: getglobalhistoricalweeklyquotesrangeextended-get
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
      - Global
      - Historical
      - Weekly
      - Quotes
      - Range
      - Extended
  /GetGlobalHistoricalQuarterlyQuotesRange:
    get:
      summary: Get Global Historical Quarterly Quotes Range
      description: Returns a range of quarterly Global Historical quotes for a security.
        For more information, go to http://www.xignite.com/
      operationId: postGetglobalhistoricalquarterlyquotesrange
      x-api-path-slug: getglobalhistoricalquarterlyquotesrange-get
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
      - Global
      - Historical
      - Quarterly
      - Quotes
      - Range
  /GetGlobalHistoricalMonthlyQuotesRange:
    get:
      summary: Get Global Historical Monthly Quotes Range
      description: This operation returns a range of monthly quotes for an equity
        based on the specified date range. This includes the adjusted price as specified.
      operationId: postGetglobalhistoricalmonthlyquotesrange
      x-api-path-slug: getglobalhistoricalmonthlyquotesrange-get
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
      - Global
      - Historical
      - Monthly
      - Quotes
      - Range
  /GetGlobalHistoricalMonthlyQuotesRangeExtended:
    get:
      summary: Get Global Historical Monthly Quotes Range Extended
      description: This operation returns a range of monthly quotes extended for an
        equity based on the specified date range. This includes the adjusted price
        as specified.
      operationId: postGetglobalhistoricalmonthlyquotesrangeextended
      x-api-path-slug: getglobalhistoricalmonthlyquotesrangeextended-get
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
      - Global
      - Historical
      - Monthly
      - Quotes
      - Range
      - Extended
  /GetGlobalHistoricalQuote:
    get:
      summary: Get Global Historical Quote
      description: Returns a quote as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetglobalhistoricalquote
      x-api-path-slug: getglobalhistoricalquote-get
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
      - Global
      - Historical
      - Quote
  /GetEndOfDayQuote:
    get:
      summary: Get End Of Day Quote
      description: Returns a quote as of a historical date. This includes the adjusted
        price as specified.
      operationId: postGetendofdayquote
      x-api-path-slug: getendofdayquote-get
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
      - End
      - Of
      - Day
      - Quote
  /GetRealTimeMetalQuotes:
    get:
      summary: Get Real Time Metal Quotes
      description: Get real time exchange rate.
      operationId: GetRealTimeMetalQuotes
      x-api-path-slug: getrealtimemetalquotes-get
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
      - Real
      - Time
      - Metal
      - Quotes
  /GetHistoricalMetalQuotes:
    get:
      summary: Get Historical Metal Quotes
      description: Get cross sectional historical metal quotes at a given time.
      operationId: GetHistoricalMetalQuotes
      x-api-path-slug: gethistoricalmetalquotes-get
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
      - Metal
      - Quotes
  /GetLatestHistoricalMetalQuotes:
    get:
      summary: Get Latest Historical Metal Quotes
      description: Get cross sectional historical metal quotes by a given time.
      operationId: GetLatestHistoricalMetalQuotes
      x-api-path-slug: getlatesthistoricalmetalquotes-get
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
      - Historical
      - Metal
      - Quotes
  /GetHistoricalMetalQuotesRange:
    get:
      summary: Get Historical Metal Quotes Range
      description: Get historical metal quotes time series.
      operationId: GetHistoricalMetalQuotesRange
      x-api-path-slug: gethistoricalmetalquotesrange-get
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
      - Metal
      - Quotes
      - Range
  /GetLondonHistoricalMetalQuotesRange:
    get:
      summary: Get London Historical Metal Quotes Range
      description: Get historical metal quotes based on Legacy London spot prices.
      operationId: GetLondonHistoricalMetalQuotesRange
      x-api-path-slug: getlondonhistoricalmetalquotesrange-get
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
      - London
      - Historical
      - Metal
      - Quotes
      - Range
  /GetRealTimeMetalQuote:
    get:
      summary: Get Real Time Metal Quote
      description: Get real time metal quote.
      operationId: GetRealTimeMetalQuote
      x-api-path-slug: getrealtimemetalquote-get
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
      - Real
      - Time
      - Metal
      - Quote
  /GetRealTimeExtendedMetalQuote:
    get:
      summary: Get Real Time Extended Metal Quote
      description: Get real time extended metal quote.
      operationId: GetRealTimeExtendedMetalQuote
      x-api-path-slug: getrealtimeextendedmetalquote-get
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
      - Real
      - Time
      - Extended
      - Metal
      - Quote
  /GetHistoricalMetalQuote:
    get:
      summary: Get Historical Metal Quote
      description: Get historical metal quote at a given time.
      operationId: GetHistoricalMetalQuote
      x-api-path-slug: gethistoricalmetalquote-get
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
      - Metal
      - Quote
  /GetLatestHistoricalMetalQuote:
    get:
      summary: Get Latest Historical Metal Quote
      description: Get historical metal quote by a given time.
      operationId: GetLatestHistoricalMetalQuote
      x-api-path-slug: getlatesthistoricalmetalquote-get
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
      - Historical
      - Metal
      - Quote
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