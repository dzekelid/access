---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Core API Access code generation
  description: Generates a new access code. If it is of type 'userAccessCode', the
    provided userId must reference an user within authorized scopes. This access code
    can then be used to access the targetted application without re-typing credentials
    (ThingPark SSO). In order to do so, the code needs to be appended to the application
    portal URL, i.e. 'portalUrl?userAccessCode=code'.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /core/v141/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accessCodes:
    post:
      summary: Access code generation
      description: Generates a new access code. If it is of type 'userAccessCode',
        the provided userId must reference an user within authorized scopes. This
        access code can then be used to access the targetted application without re-typing
        credentials (ThingPark SSO). In order to do so, the code needs to be appended
        to the application portal URL, i.e. 'portalUrl?userAccessCode=code'.
      operationId: generates-a-new-access-code-if-it-is-of-type-useraccesscode-the-provided-userid-must-reference-an-us
      x-api-path-slug: accesscodes-post
      parameters:
      - in: body
        name: accessCode
        description: Information about the access code to generate
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Access
      - Code
      - Generation
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---