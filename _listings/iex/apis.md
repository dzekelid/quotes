---
name: IEX
x-slug: iex
description: IEX, the Investors Exchange, is a fair, simple and transparent stock
  exchange dedicated to investor and issuer protection.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
x-kinRank: "9"
x-alexaRank: "166667"
tags: Quotes
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/apis.md
specificationVersion: "0.14"
apis:
- name: IEX - Batch Requests
  x-api-slug: stockmarketbatch-get
  description: Returns batch stock quotes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stockmarketbatch-get-openapi.md
- name: IEX - Delayed Quote
  x-api-slug: stocksymboldelayedquote-get
  description: This returns the 15 minute delayed market quote.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stocksymboldelayedquote-get-openapi.md
- name: IEX - List
  x-api-slug: stocksymbollist-get
  description: Refer to the quote section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stocksymbollist-get-openapi.md
- name: IEX - Previous
  x-api-slug: stocksymbolprevious-get
  description: This returns previous day adjusted price data for a single stock, or
    an object keyed by symbol of price data for the whole market.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stocksymbolprevious-get-openapi.md
- name: IEX - Quote
  x-api-slug: stocksymbolquote-get
  description: Pulls a stock quote using any ticker symbol.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stocksymbolquote-get-openapi.md
- name: IEX - Splits
  x-api-slug: stocksymbolsplitsrange-get
  description: Returns stock splits for any date range using ticker symbol.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Marketplace, Market Data, Data Provider, API Provider, Financial Services,
    Profiles, General Data, Service API, Relative Data, Pedestal, Historical Data
    API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/quotes/master/_listings/iex/stocksymbolsplitsrange-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://idx.broker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://iex.stack.network
- type: x-authentication
  url: https://iextrading.com/developer/docs/#authentication
- type: x-blog
  url: https://medium.com/boxes-and-lines
- type: x-blog-rss
  url: view-source:https://medium.com/feed/boxes-and-lines
- type: x-branding
  url: https://iextrading.com/brand/
- type: x-change-log
  url: https://iextrading.com/developer/docs/#changelog
- type: x-crunchbase
  url: https://crunchbase.com/organization/iex
- type: x-developer
  url: https://iextrading.com/developer/docs/
- type: x-email
  url: sales@iextrading.com
- type: x-email
  url: listings@iextrading.com
- type: x-email
  url: marketops@iextrading.com
- type: x-email
  url: sre@iextrading.com
- type: x-email
  url: marcomms@iextrading.com
- type: x-email
  url: info@iextrading.com
- type: x-email
  url: api@iextrading.com
- type: x-email
  url: legal@iextrading.com
- type: x-email
  url: ventures@iextrading.com
- type: x-faq
  url: https://iextrading.com/faq/
- type: x-github
  url: https://github.com/iexg
- type: x-linkedin
  url: https://www.linkedin.com/company/iex-group-inc-
- type: x-press
  url: https://iextrading.com/about/press/
- type: x-road-map
  url: https://iextrading.com/developer/docs/#roadmap
- type: x-terms-of-service
  url: https://iextrading.com/developer/docs/#terms
- type: x-twitter
  url: https://twitter.com/IEX
- type: x-website
  url: https://iextrading.com
- type: x-websockets
  url: https://iextrading.com/developer/docs/#websockets
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---