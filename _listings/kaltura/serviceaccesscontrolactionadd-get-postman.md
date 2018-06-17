{
  "info": {
    "name": "Kaltura VPaaS Get Service Access Control Action Add",
    "_postman_id": "f645e12d-34a6-4cd1-9c20-0e301371cd84",
    "description": "Add new Access Control Profile",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "e475b6ad-5f43-4a01-835f-79c9186dce55",
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
              "id": "c420b5ff-1779-4bec-919e-cf6f3dbf5be9"
            }
          ]
        }
      ]
    }
  ]
}