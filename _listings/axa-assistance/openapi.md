---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services-trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sales/v1/individual/travel/quotes:
    post:
      summary: Create new individual travel quote for sales
      description: Create new individual travel quote for sales
      operationId: postSalesV1IndividualTravelQuotes
      x-api-path-slug: salesv1individualtravelquotes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - new
      - individual
      - travel
      - quotesales
  /service/vexp/roadside/quotes/search:
    post:
      summary: Search quotes for a roadside service.
      description: Search quotes for a roadside service.
      operationId: postServiceVexpRoadsideQuotesSearch
      x-api-path-slug: servicevexproadsidequotessearch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Search
      - quotesa
      - roadside
      - service.
---