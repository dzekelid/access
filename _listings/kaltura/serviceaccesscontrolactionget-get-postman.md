{
  "info": {
    "name": "Kaltura VPaaS Get Service Access Control Action Get",
    "_postman_id": "5f88a55a-64bb-4f73-8138-b9c5bdb688d9",
    "description": "Get Access Control Profile by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "67fc525a-117c-42bb-86f0-0387eba13ce9",
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
              "id": "f4ff6ba8-3e92-49cb-9ff5-79f07059bc6a"
            }
          ]
        },
        {
          "id": "83827799-ac17-40d9-9cd3-2e4d93747b9e",
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
              "id": "51de0c9c-7dde-4f63-8ee5-14ec2d005a29"
            }
          ]
        },
        {
          "id": "acb35fef-0dca-41d4-a0ef-ed600bbd2412",
          "name": "accessControl.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "317a8f85-8ebb-492b-9660-514160acb41e"
            }
          ]
        }
      ]
    }
  ]
}