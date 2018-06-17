---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Release Access Restrictions
  description: Release downloaded content access restriction.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /myconfig/releaseDownloadAccess:
    post:
      summary: Release Access Restrictions
      description: Release downloaded content access restriction.
      operationId: books.myconfig.releaseDownloadAccess
      x-api-path-slug: myconfigreleasedownloadaccess-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to release the restriction
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeIds
        description: The volume(s) to release restrictions for
      responses:
        200:
          description: OK
      tags:
      - Access
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