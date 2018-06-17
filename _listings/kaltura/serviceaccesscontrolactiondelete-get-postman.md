{
  "info": {
    "name": "Kaltura VPaaS Get Service Access Control Action Delete",
    "_postman_id": "834f367d-39d3-4716-8540-bae8d994c3ec",
    "description": "Delete Access Control Profile by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "c8043df5-c34e-4b77-8559-022dd8c74f1a",
          "name": "accessControl.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/add?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Access Control Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "211bab22-fa91-4d89-b16d-20d31bf8af52"
            }
          ]
        },
        {
          "id": "657d6c58-34d8-4f56-b5c6-b1d663114cdf",
          "name": "accessControl.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fe2556b-5111-460e-9533-c8fbb2e3863f"
            }
          ]
        }
      ]
    }
  ]
}