---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 0
info:
  title: AWS CloudSearch Describe Service Access Policies
  version: 1.0.0
  description: Gets information about the access policies that control access to the
    domain's document and search endpoints.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeServiceAccessPolicies:
    get:
      summary: Describe Service Access Policies
      description: Gets information about the access policies that control access
        to the domain's document and search endpoints.
      operationId: DescribeServiceAccessPolicies
      x-api-path-slug: actiondescribeserviceaccesspolicies-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Access Policies
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