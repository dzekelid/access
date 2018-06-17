---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 1
info:
  title: AWS CloudSearch
  version: 1.0.0
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
  /?Action=UpdateServiceAccessPolicies:
    get:
      summary: Update Service Access Policies
      description: Configures the access rules that control access to the domain's
        document and search endpoints.
      operationId: UpdateServiceAccessPolicies
      x-api-path-slug: actionupdateserviceaccesspolicies-get
      parameters:
      - in: query
        name: AccessPolicies
        description: The access rules you want to configure
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Access Policies
---