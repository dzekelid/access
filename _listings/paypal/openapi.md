---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 1
info:
  title: PayPal (Sandbox)
  description: bring-payments-to-apps-mobile-and-social-with-adaptive-payments-bsandbox-api-b
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Permissions/GetAccessToken:
    post:
      summary: GetAccess Token
      description: Use the GetAccessToken API operation to obtain an access token
        for a set of permissions.
      operationId: Permissions.GetAccessToken.post
      x-api-path-slug: permissionsgetaccesstoken-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Access Tokens
---