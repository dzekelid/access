swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events/{id}/access_codes/:
    get:
      summary: Get Events Access Codes
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
      operationId: getEventsAccessCodes
      x-api-path-slug: eventsidaccess-codes-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Access
      - Codes
    post:
      summary: Post Events Access Codes
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
      operationId: postEventsAccessCodes
      x-api-path-slug: eventsidaccess-codes-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Access
      - Codes
    delete:
      summary: Delete Events Access Codes
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
      operationId: deleteEventsAccessCodes
      x-api-path-slug: eventsidaccess-codes-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Access
      - Codes
  /events/{id}/access_codes/:access_code_id/:
    get:
      summary: Get Events Access Codes Access Code
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: getEventsAccessCodesAccessCode
      x-api-path-slug: eventsidaccess-codesaccess-code-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Access
      - Codes
      - :access
      - Code
    post:
      summary: Post Events Access Codes Access Code
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: postEventsAccessCodesAccessCode
      x-api-path-slug: eventsidaccess-codesaccess-code-id-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Access
      - Codes
      - :access
      - Code