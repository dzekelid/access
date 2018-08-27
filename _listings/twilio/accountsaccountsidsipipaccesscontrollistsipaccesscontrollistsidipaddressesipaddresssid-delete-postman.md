{
  "info": {
    "name": "Twilio Delete SIP IP Access Control List IP Address",
    "_postman_id": "ca1f3a02-81e9-4c5c-ae6f-966e0d2a28cb",
    "description": "Deletes an IP address entry from the list.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "sip ip access control lists",
      "item": [
        {
          "id": "012513cb-b267-410d-994c-7d5015f95f2c",
          "name": "deletes-an-ip-address-entry-from-the-list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses/:IpAddressSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAddressSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an IP address entry from the list"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"uri\": \"uri\",\r\n    \"firstpageuri\": \"firstpageuri\",\r\n    \"nextpageuri\": \"nextpageuri\",\r\n    \"previouspageuri\": \"previouspageuri\",\r\n    \"page\": \"page\",\r\n    \"pagesize\": \"pagesize\",\r\n    \"ip_addresses\": {}\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "8e1fbafb-e6eb-4a7b-8563-3371a0d1df3f"
            }
          ]
        }
      ]
    }
  ]
}