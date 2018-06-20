---
name: Barchart
x-slug: barchart
description: Barchart.com is the leading provider of intraday stock and commodities
  real-time or delayed charts with powerful indicators and technical analysis.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
x-kinRank: "7"
x-alexaRank: "15739"
tags: Quotes
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/barchart/apis.md
specificationVersion: "0.14"
apis:
- name: Barchart API Get Quote
  x-api-slug: barchart-api
  description: The getQuote API is used to request price data, either real-time, delayed
    or end-of-day, by symbol. In addition to Last Price or Settlement, other fields
    such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com////getQuote.json
  tags: Quotes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/barchart/getquote-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/barchart/getquote-json-get-openapi.md
- name: Barchart API
  x-api-slug: barchart-api
  description: Barchart.com is the leading provider of intraday stock and commodities
    real-time or delayed charts with powerful indicators and technical analysis.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/barchart/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/barchart-com
- type: x-email
  url: solutions@barchart.com
- type: x-email
  url: careers@barchart.com
- type: x-email
  url: colleen.sheeren@barchart.com
- type: x-github
  url: https://github.com/barchart
- type: x-twitter
  url: https://twitter.com/Barchart
- type: x-website
  url: https://www.barchart.com
- type: x-websockets
  url: https://github.com/barchart/barchart-ondemand-client-js
- type: x-website
  url: http://www.barchart.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---