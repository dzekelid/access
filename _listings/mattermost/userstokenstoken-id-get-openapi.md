---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get a user access token
  description: |-
    Get a user access token. Does not include the actual authentication token.

    __Minimum server version__: 4.1

    ##### Permissions
    Must have `read_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/tokens:
    post:
      summary: Create a user access token
      description: |-
        Generate a user access token that can be used to authenticate with the Mattermost REST API.

        __Minimum server version__: 4.1

        ##### Permissions
        Must have `create_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: generate-a-user-access-token-that-can-be-used-to-authenticate-with-the-mattermost-rest-api-minimum-s
      x-api-path-slug: usersuser-idtokens-post
      parameters:
      - in: body
        name: token
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - User
      - Access
      - Token
    get:
      summary: Get user access tokens
      description: |-
        Get a list of user access tokens for a user. Does not include the actual authentication tokens. Use query paremeters for paging.

        __Minimum server version__: 4.1

        ##### Permissions
        Must have `read_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: get-a-list-of-user-access-tokens-for-a-user-does-not-include-the-actual-authentication-tokens-use-qu
      x-api-path-slug: usersuser-idtokens-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of tokens per page
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - User
      - Access
      - Tokens
  /users/tokens:
    get:
      summary: Get user access tokens
      description: |-
        Get a page of user access tokens for users on the system. Does not include the actual authentication tokens. Use query parameters for paging.

        __Minimum server version__: 4.7

        ##### Permissions
        Must have `manage_system` permission.
      operationId: get-a-page-of-user-access-tokens-for-users-on-the-system-does-not-include-the-actual-authentication-
      x-api-path-slug: userstokens-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of tokens per page
      responses:
        200:
          description: OK
      tags:
      - User
      - Access
      - Tokens
  /users/tokens/revoke:
    post:
      summary: Revoke a user access token
      description: |-
        Revoke a user access token and delete any sessions using the token.

        __Minimum server version__: 4.1

        ##### Permissions
        Must have `revoke_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: revoke-a-user-access-token-and-delete-any-sessions-using-the-token-minimum-server-version--41-permis
      x-api-path-slug: userstokensrevoke-post
      parameters:
      - in: body
        name: token
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Revoke
      - User
      - Access
      - Token
  /users/tokens/{token_id}:
    get:
      summary: Get a user access token
      description: |-
        Get a user access token. Does not include the actual authentication token.

        __Minimum server version__: 4.1

        ##### Permissions
        Must have `read_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: get-a-user-access-token-does-not-include-the-actual-authentication-token-minimum-server-version--41-
      x-api-path-slug: userstokenstoken-id-get
      parameters:
      - in: path
        name: token_id
        description: User access token GUID
      responses:
        200:
          description: OK
      tags:
      - User
      - Access
      - Token
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