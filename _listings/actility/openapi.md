swagger: "2.0"
x-collection-name: Actility
x-complete: 1
info:
  title: ThingPark DX Maker API
  description: api-providing-features-for-device-makers-such-as-preprovisioning-on-standalone-join-servers-
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /maker/v011/api
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
    get:
      summary: Access code validation
      description: Validates the access code value and retrieves extended access code
        information such as user information.
      operationId: validates-the-access-code-value-and-retrieves-extended-access-code-information-such-as-user-informat
      x-api-path-slug: accesscodes-get
      parameters:
      - in: query
        name: applicationId
        description: Id of the application targetted by the access code to validate
      - in: query
        name: applicationRef
        description: Ref of the application targetted by the access code to validate
      - in: query
        name: type
        description: Type of the access code to validate
      - in: query
        name: value
        description: Value of the access code to validate
      responses:
        200:
          description: OK
      tags:
      - Access
      - Code
      - Validation