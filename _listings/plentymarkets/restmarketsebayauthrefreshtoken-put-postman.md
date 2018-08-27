{
  "info": {
    "name": "Plentymarkets Refresh an expired access token.",
    "_postman_id": "0ef255ce-842d-480b-93ef-72fed18e566e",
    "description": "Refresh an expired access token..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Refresh",
      "item": [
        {
          "id": "7092b236-4d80-41f8-87c7-56d882ea891e",
          "name": "putRestMarketsEbayAuthRefreshToken",
          "request": {
            "url": "http://example.com/rest/markets/ebay/auth/refresh-token",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Refresh an expired access token.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "154afd95-07b3-419d-905c-fe91efceab6a"
            }
          ]
        }
      ]
    }
  ]
}