---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 1
info:
  title: Books
  description: searches-for-books-and-manages-your-google-books-library-
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
  /myconfig/requestAccess:
    post:
      summary: Request Access
      description: Request concurrent and download access restrictions.
      operationId: books.myconfig.requestAccess
      x-api-path-slug: myconfigrequestaccess-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to request the restrictions
      - in: query
        name: licenseTypes
        description: The type of access license to request
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: nonce
        description: The client nonce value
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: The volume to request concurrent/download restrictions for
      responses:
        200:
          description: OK
      tags:
      - Access
---