swagger: "2.0"
x-collection-name: uebermaps
x-complete: 1
info:
  title: uebermaps
  description: enable-people-to-store-spots-on-public-and-private-maps
  termsOfService: https://uebermaps.com/terms/
  contact:
    name: uebermaps API Team
  version: "2.0"
host: uebermaps.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /share/map/{id}:
    get:
      summary: Get secret access token to share map
      description: Get secret access token of an uebermap with access set to 'Secret
        link'. Pass the 'token' on every request you make to access this uebermap
        and its resources. F.e. token=1-x_gqu7eLBe3uKoAGAGXy
      operationId: share.map.id.get
      x-api-path-slug: sharemapid-get
      parameters:
      - in: path
        name: id
        description: Id of map
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Secret
      - Access
      - Token
      - To
      - Share
      - Map