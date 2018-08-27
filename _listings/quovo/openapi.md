swagger: "2.0"
x-collection-name: Quovo
x-complete: 1
info:
  title: Quovo API v3
  description: todo-add-description
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tokens:
    get:
      summary: Get all active access tokens
      description: Retrieves all of your current Access Tokens.
      operationId: TokensGet
      x-api-path-slug: tokens-get
      responses:
        200:
          description: OK
      tags:
      - Active
      - Access
      - Tokens
    post:
      summary: Create a new access token
      description: Creates and returns a new Access Token.
      operationId: TokensPost4
      x-api-path-slug: tokens-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - New
      - Access
      - Token
    delete:
      summary: Delete an existing access token
      description: Deletes an Access Token.
      operationId: TokensDelete
      x-api-path-slug: tokens-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Existing
      - Access
      - Token