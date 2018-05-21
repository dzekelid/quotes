---
name: Xignite
x-slug: xignite
description: Financial market data on-demand. Xignite financial Web services help
  build smarter websites and applications in minutes with zero up-front investment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
x-kinRank: "9"
x-alexaRank: "383974"
tags: Quotes
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/apis.md
specificationVersion: "0.14"
apis:
- name: Xignite BATS Real Time Get Real Quotes
  x-api-slug: xignite-bats-real-time
  description: Returns a collection of real time stock quotes for a comma-separated
    list of stock quotes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://batsrealtime.xignite.com/xBATSRealTime.json/XigniteBATSRealTime//GetRealQuotes
  tags: Real, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getrealquotes-post-openapi.md
- name: Xignite BATS Real Time Get Real Quotes By Identifiers
  x-api-slug: xignite-bats-real-time
  description: Returns a collection of real time stock quotes for a comma-separated
    list of stock quotes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://batsrealtime.xignite.com/xBATSRealTime.json/XigniteBATSRealTime//GetRealQuotesByIdentifiers
  tags: Real, Quotes, Identifiers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getrealquotesbyidentifiers-post-openapi.md
- name: Xignite BATS Real Time
  x-api-slug: xignite-bats-real-time
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://batsrealtime.xignite.com/xBATSRealTime.json/XigniteBATSRealTime
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Global Futures Get Future Quotes
  x-api-slug: xignite-global-futures
  description: Returns delayed quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetFutureQuotes
  tags: Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getfuturequotes-post-openapi.md
- name: Xignite Global Futures Get Latest Future Quotes
  x-api-slug: xignite-global-futures
  description: Returns latest delayed quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetLatestFutureQuotes
  tags: Latest, Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfuturequotes-post-openapi.md
- name: Xignite Global Futures Get Latest Front Month Future Quotes
  x-api-slug: xignite-global-futures
  description: Returns latest quotes for front month futures
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetLatestFrontMonthFutureQuotes
  tags: Latest, Front, Month, Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfrontmonthfuturequotes-post-openapi.md
- name: Xignite Global Futures Get All Future Quotes
  x-api-slug: xignite-global-futures
  description: Returns all delayed future quotes for a future base.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetAllFutureQuotes
  tags: Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getallfuturequotes-post-openapi.md
- name: Xignite Global Futures Get All Option Quotes
  x-api-slug: xignite-global-futures
  description: Returns all delayed future option quotes for a future contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetAllOptionQuotes
  tags: Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getalloptionquotes-post-openapi.md
- name: Xignite Global Futures Get Future Option Quotes
  x-api-slug: xignite-global-futures
  description: Returns delayed future option quotes for multiple future options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetFutureOptionQuotes
  tags: Future, Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getfutureoptionquotes-post-openapi.md
- name: Xignite Global Futures Get Latest Future Option Quotes
  x-api-slug: xignite-global-futures
  description: Returns latest delayed quotes for multiple future options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetLatestFutureOptionQuotes
  tags: Latest, Future, Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfutureoptionquotes-post-openapi.md
- name: Xignite Global Futures Get Historical Swap Quotes
  x-api-slug: xignite-global-futures
  description: Returns historical swap quotes within a date range
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetHistoricalSwapQuotes
  tags: Historical, Swap, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalswapquotes-post-openapi.md
- name: Xignite Global Futures Get Historical Future Quotes Range
  x-api-slug: xignite-global-futures
  description: Returns historical future quotes on a future contract within a date
    range
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures//GetHistoricalFutureQuotesRange
  tags: Historical, Future, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalfuturequotesrange-post-openapi.md
- name: Xignite Global Futures
  x-api-slug: xignite-global-futures
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalfutures.xignite.com/xGlobalFutures.json/XigniteGlobalFutures
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Global Historical Get End Of Day Quotes
  x-api-slug: xignite-global-historical
  description: Returns a quote as of a historical date. This includes the adjusted
    price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetEndOfDayQuotes
  tags: End, Of, Day, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getendofdayquotes-post-openapi.md
- name: Xignite Global Historical Get End Of Day Quotes Range
  x-api-slug: xignite-global-historical
  description: Returns a quote a complete range of stock quotes for a given equity.
    This includes the adjusted price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetEndOfDayQuotesRange
  tags: End, Of, Day, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getendofdayquotesrange-post-openapi.md
- name: Xignite Global Historical Get Global Historical Quotes
  x-api-slug: xignite-global-historical
  description: Returns quotes as of a historical date. This includes the adjusted
    price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalQuotes
  tags: Global, Historical, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalquotes-post-openapi.md
- name: Xignite Global Historical Get Global Historical Quotes As Of
  x-api-slug: xignite-global-historical
  description: This operation returns a range of quotes for a security.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalQuotesAsOf
  tags: Global, Historical, Quotes, As, Of
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalquotesasof-post-openapi.md
- name: Xignite Global Historical Get Global Historical Quotes Range
  x-api-slug: xignite-global-historical
  description: This operation returns a complete range of stock quotes for a given
    equity. This includes the adjusted price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalQuotesRange
  tags: Global, Historical, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalquotesrange-post-openapi.md
- name: Xignite Global Historical Get Global Historical Quotes Range Extended
  x-api-slug: xignite-global-historical
  description: This operation returns a complete range of global historical quotes
    extended for a given equity. This includes the adjusted price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalQuotesRangeExtended
  tags: Global, Historical, Quotes, Range, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalquotesrangeextended-post-openapi.md
- name: Xignite Global Historical Get Global Historical Weekly Quotes Range
  x-api-slug: xignite-global-historical
  description: Returns a range of weekly Global Historical quotes for a security.
    For more information, go to http://www.xignite.com/
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalWeeklyQuotesRange
  tags: Global, Historical, Weekly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalweeklyquotesrange-post-openapi.md
- name: Xignite Global Historical Get Global Historical Weekly Quotes Range Extended
  x-api-slug: xignite-global-historical
  description: Returns a range of weekly Global Historical quotes extended for a security.
    For more information, go to http://www.xignite.com/
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalWeeklyQuotesRangeExtended
  tags: Global, Historical, Weekly, Quotes, Range, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalweeklyquotesrangeextended-post-openapi.md
- name: Xignite Global Historical Get Global Historical Quarterly Quotes Range
  x-api-slug: xignite-global-historical
  description: Returns a range of quarterly Global Historical quotes for a security.
    For more information, go to http://www.xignite.com/
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalQuarterlyQuotesRange
  tags: Global, Historical, Quarterly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalquarterlyquotesrange-post-openapi.md
- name: Xignite Global Historical Get Global Historical Monthly Quotes Range
  x-api-slug: xignite-global-historical
  description: This operation returns a range of monthly quotes for an equity based
    on the specified date range. This includes the adjusted price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalMonthlyQuotesRange
  tags: Global, Historical, Monthly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalmonthlyquotesrange-post-openapi.md
- name: Xignite Global Historical Get Global Historical Monthly Quotes Range Extended
  x-api-slug: xignite-global-historical
  description: This operation returns a range of monthly quotes extended for an equity
    based on the specified date range. This includes the adjusted price as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalHistoricalMonthlyQuotesRangeExtended
  tags: Global, Historical, Monthly, Quotes, Range, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getglobalhistoricalmonthlyquotesrangeextended-post-openapi.md
- name: Xignite Global Historical
  x-api-slug: xignite-global-historical
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Global Metals Get Real Time Metal Quotes
  x-api-slug: xignite-global-metals
  description: Get real time exchange rate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals//GetRealTimeMetalQuotes
  tags: Real, Time, Metal, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getrealtimemetalquotes-post-openapi.md
- name: Xignite Global Metals Get Historical Metal Quotes
  x-api-slug: xignite-global-metals
  description: Get cross sectional historical metal quotes at a given time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals//GetHistoricalMetalQuotes
  tags: Historical, Metal, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalmetalquotes-post-openapi.md
- name: Xignite Global Metals Get Latest Historical Metal Quotes
  x-api-slug: xignite-global-metals
  description: Get cross sectional historical metal quotes by a given time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals//GetLatestHistoricalMetalQuotes
  tags: Latest, Historical, Metal, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatesthistoricalmetalquotes-post-openapi.md
- name: Xignite Global Metals Get Historical Metal Quotes Range
  x-api-slug: xignite-global-metals
  description: Get historical metal quotes time series.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals//GetHistoricalMetalQuotesRange
  tags: Historical, Metal, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalmetalquotesrange-post-openapi.md
- name: Xignite Global Metals Get London Historical Metal Quotes Range
  x-api-slug: xignite-global-metals
  description: Get historical metal quotes based on Legacy London spot prices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals//GetLondonHistoricalMetalQuotesRange
  tags: London, Historical, Metal, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlondonhistoricalmetalquotesrange-post-openapi.md
- name: Xignite Global Metals
  x-api-slug: xignite-global-metals
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalmetals.xignite.com/xGlobalMetals.json/XigniteGlobalMetals
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Global Real Time Futures Get Future Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns realtime quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetFutureQuotes
  tags: Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getfuturequotes-post-openapi.md
- name: Xignite Global Real Time Futures Get Latest Future Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns latest realtime quotes for multiple future contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetLatestFutureQuotes
  tags: Latest, Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfuturequotes-post-openapi.md
- name: Xignite Global Real Time Futures Get Latest Front Month Future Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns latest quotes for front month futures
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetLatestFrontMonthFutureQuotes
  tags: Latest, Front, Month, Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfrontmonthfuturequotes-post-openapi.md
- name: Xignite Global Real Time Futures Get All Future Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns all delayed future quotes for a future base.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetAllFutureQuotes
  tags: Future, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getallfuturequotes-post-openapi.md
- name: Xignite Global Real Time Futures Get All Option Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns all realtime future option quotes for a future contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetAllOptionQuotes
  tags: Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getalloptionquotes-post-openapi.md
- name: Xignite Global Real Time Futures Get Future Option Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns realtime future option quotes for multiple future options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetFutureOptionQuotes
  tags: Future, Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getfutureoptionquotes-post-openapi.md
- name: Xignite Global Real Time Futures Get Latest Future Option Quotes
  x-api-slug: xignite-global-real-time-futures
  description: Returns latest realtime quotes for multiple future options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures//GetLatestFutureOptionQuotes
  tags: Latest, Future, Option, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getlatestfutureoptionquotes-post-openapi.md
- name: Xignite Global Real Time Futures
  x-api-slug: xignite-global-real-time-futures
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://globalrealtimefutures.xignite.com/xGlobalRealTimeFutures.json/XigniteGlobalRealTimeFutures
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Historical Get Historical Quotes Adjusted
  x-api-slug: xignite-historical
  description: Returns a quote as of a historical date. This includes split and dividends
    adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotesAdjusted
  tags: Historical, Quotes, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotesadjusted-post-openapi.md
- name: Xignite Historical Get Historical Monthly Quotes Range Adjusted
  x-api-slug: xignite-historical
  description: This operation returns end of month quotes for a US equity. This includes
    split and dividends adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalMonthlyQuotesRangeAdjusted
  tags: Historical, Monthly, Quotes, Range, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalmonthlyquotesrangeadjusted-post-openapi.md
- name: Xignite Historical Get Historical Quotes As Of Adjusted
  x-api-slug: xignite-historical
  description: This operation returns a range of quotes for a security. This includes
    split and dividends adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotesAsOfAdjusted
  tags: Historical, Quotes, As, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotesasofadjusted-post-openapi.md
- name: Xignite Historical Get Historical Quotes Range Adjusted
  x-api-slug: xignite-historical
  description: This operation returns a complete range of stock quotes for a US equity.
    This includes and dividends adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotesRangeAdjusted
  tags: Historical, Quotes, Range, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotesrangeadjusted-post-openapi.md
- name: Xignite Historical Get Historical Weekly Quotes Range Adjusted
  x-api-slug: xignite-historical
  description: This operation returns end of week quotes for a US equity. This includes
    split and dividends adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalWeeklyQuotesRangeAdjusted
  tags: Historical, Weekly, Quotes, Range, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalweeklyquotesrangeadjusted-post-openapi.md
- name: Xignite Historical Get Historical Quarterly Quotes Range Adjusted
  x-api-slug: xignite-historical
  description: This operation returns end of quarter quotes for a US equity. This
    includes split and dividends adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuarterlyQuotesRangeAdjusted
  tags: Historical, Quarterly, Quotes, Range, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquarterlyquotesrangeadjusted-post-openapi.md
- name: Xignite Historical Get Historical Quotes
  x-api-slug: xignite-historical
  description: Returns a quote as of a historical date. This includes split adjusted
    price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotes
  tags: Historical, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotes-post-openapi.md
- name: Xignite Historical Get Historical Quotes As Of
  x-api-slug: xignite-historical
  description: This operation returns a range of quotes for a security.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotesAsOf
  tags: Historical, Quotes, As, Of
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotesasof-post-openapi.md
- name: Xignite Historical Get Historical Quotes Range
  x-api-slug: xignite-historical
  description: This operation returns a complete range of stock quotes for a US equity.
    This includes split adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuotesRange
  tags: Historical, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquotesrange-post-openapi.md
- name: Xignite Historical Get Historical Monthly Quotes Range
  x-api-slug: xignite-historical
  description: This operation returns end of month quotes for a US equity. This includes
    split adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalMonthlyQuotesRange
  tags: Historical, Monthly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalmonthlyquotesrange-post-openapi.md
- name: Xignite Historical Get Historical Weekly Quotes Range
  x-api-slug: xignite-historical
  description: This operation returns end of week quotes for a US equity. This includes
    split adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalWeeklyQuotesRange
  tags: Historical, Weekly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalweeklyquotesrange-post-openapi.md
- name: Xignite Historical Get Historical Quarterly Quotes Range
  x-api-slug: xignite-historical
  description: This operation returns end of quarter quotes for a US equity. This
    includes split adjusted price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetHistoricalQuarterlyQuotesRange
  tags: Historical, Quarterly, Quotes, Range
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/gethistoricalquarterlyquotesrange-post-openapi.md
- name: Xignite Historical
  x-api-slug: xignite-historical
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite NASDAQ Last Sale Get Quotes
  x-api-slug: xignite-nasdaq-last-sale
  description: Returns real-time NASDAQ BASIC quotes for given securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://nasdaqlastsale.xignite.com/xNASDAQLastSale.json/XigniteNASDAQLastSale//GetQuotes
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getquotes-post-openapi.md
- name: Xignite NASDAQ Last Sale Get Extended Quotes
  x-api-slug: xignite-nasdaq-last-sale
  description: Returns real-time NASDAQ BASIC quotes for given securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://nasdaqlastsale.xignite.com/xNASDAQLastSale.json/XigniteNASDAQLastSale//GetExtendedQuotes
  tags: Extended, Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getextendedquotes-post-openapi.md
- name: Xignite NASDAQ Last Sale
  x-api-slug: xignite-nasdaq-last-sale
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://nasdaqlastsale.xignite.com/xNASDAQLastSale.json/XigniteNASDAQLastSale
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
- name: Xignite Super Quotes Get Quotes
  x-api-slug: xignite-super-quotes
  description: Returns quotes for given securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://superquotes.xignite.com/xSuperQuotes.json/XigniteSuperQuotes//GetQuotes
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/getquotes-post-openapi.md
- name: Xignite Super Quotes
  x-api-slug: xignite-super-quotes
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://superquotes.xignite.com/xSuperQuotes.json/XigniteSuperQuotes
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/xignite/openapi.md
x-common:
- type: x-net-sdk
  url: http://xignite.github.io/DotNetSDK/
- type: x-base
  url: http://globalmaster.xignite.com
- type: x-case-studies
  url: https://resources.xignite.com/case-studies
- type: x-case-studies
  url: http://www.xignite.com/market-data/resources/case-studies/
- type: x-blog
  url: https://resources.xignite.com/xignite-blog
- type: x-contact-form
  url: http://www.xignite.com/market-data/contact-us
- type: x-crunchbase
  url: http://www.crunchbase.com/company/xignite
- type: x-crunchbase
  url: https://crunchbase.com/organization/xignite
- type: x-developer
  url: http://www.xignite.com/developers
- type: x-email
  url: support@xignite.com
- type: x-email
  url: accounting@xignite.com
- type: x-email
  url: sales@xignite.com
- type: x-email
  url: marketing@xignite.com
- type: x-email
  url: info@xignite.com
- type: x-email
  url: jobs@xignite.com
- type: x-email
  url: klangstaff@xignite.com
- type: x-faq
  url: http://www.xignite.com/Support/FAQs.aspx
- type: x-getting-started
  url: http://www.xignite.com/Support/GettingStarted.aspx
- type: x-github
  url: https://github.com/Xignite
- type: x-java-sdk
  url: http://xignite.github.io/JavaSDK/
- type: x-privacy
  url: http://www.xignite.com/Documents/PrivacyPolicy.aspx
- type: x-support
  url: http://www.xignite.com/Support/SupportPlans.aspx
- type: x-blog
  url: http://www.xignite.com/market-data/blog/tech/
- type: x-blog-rss
  url: http://www.xignite.com/market-data/feed/
- type: x-terms-of-service
  url: http://www.xignite.com/Policies/SiteUseTerms.aspx
- type: x-twitter
  url: https://twitter.com/xignite
- type: x-videos
  url: http://www.xignite.com/market-data/resources/videos/
- type: x-webinar
  url: http://www.xignite.com/market-data/resources/webinars/
- type: x-webinars
  url: https://resources.xignite.com/webinars
- type: x-website
  url: http://www.xignite.com
- type: x-white-papers
  url: http://www.xignite.com/market-data/resources/white-papers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---