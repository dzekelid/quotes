---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Super Quotes
  description: the-super-quotes-service-
  version: 1.0.0
host: superquotes.xignite.com
basePath: xSuperQuotes.json/XigniteSuperQuotes
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetQuotes:
    get:
      summary: Get Quotes
      description: Returns quotes for given securities.
      operationId: GetQuotes
      x-api-path-slug: getquotes-get
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
      - Quotes
---