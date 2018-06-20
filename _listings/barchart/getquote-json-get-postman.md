{
  "info": {
    "name": "Barchart API Get Quote",
    "_postman_id": "d8e19afe-9b8a-4bf0-bf60-3ac9b5b34631",
    "description": "The getQuote API is used to request price data, either real-time, delayed or end-of-day, by symbol. In addition to Last Price or Settlement, other fields such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Quotes",
      "item": [
        {
          "id": "67d7d0b0-6e81-49cf-9497-55f53ea506f7",
          "name": "getQuote",
          "request": {
            "url": "http://marketdata.websol.barchart.com/getQuote.json?symbols=symbols",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The getQuote API is used to request price data, either real-time, delayed or end-of-day, by symbol. In addition to Last Price or Settlement, other fields such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e019111d-c522-4b93-a53c-95e22d92728c"
            }
          ]
        }
      ]
    }
  ]
}