swagger: "2.0"
x-collection-name: GitLab
x-complete: 1
info:
  title: API title
  version: 1.0.0
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/groups/{id}/access_requests:
    get:
      summary: Get Groups Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: getV3GroupsIdAccessRequests
      x-api-path-slug: v3groupsidaccess-requests-get
      parameters:
      - in: path
        name: id
        description: The group ID
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Access
      - Requests
    post:
      summary: Post Groups Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: postV3GroupsIdAccessRequests
      x-api-path-slug: v3groupsidaccess-requests-post
      parameters:
      - in: path
        name: id
        description: The group ID
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Access
      - Requests
  /v3/groups/{id}/access_requests/{user_id}/approve:
    put:
      summary: Put Groups Access Requests User Approve
      description: This feature was introduced in GitLab 8.11.
      operationId: putV3GroupsIdAccessRequestsUserIdApprove
      x-api-path-slug: v3groupsidaccess-requestsuser-idapprove-put
      parameters:
      - in: formData
        name: access_level
        description: 'A valid access level (defaults: `30`, developer access level)'
      - in: path
        name: id
        description: The group ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Access
      - Requests
      - User
      - Approve
  /v3/groups/{id}/access_requests/{user_id}:
    delete:
      summary: Delete Groups Access Requests User
      description: This feature was introduced in GitLab 8.11.
      operationId: deleteV3GroupsIdAccessRequestsUserId
      x-api-path-slug: v3groupsidaccess-requestsuser-id-delete
      parameters:
      - in: path
        name: id
        description: The group ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Access
      - Requests
      - User
  /v3/projects/{id}/access_requests:
    get:
      summary: Get Projects Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: getV3ProjectsIdAccessRequests
      x-api-path-slug: v3projectsidaccess-requests-get
      parameters:
      - in: path
        name: id
        description: The project ID
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
    post:
      summary: Post Projects Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: postV3ProjectsIdAccessRequests
      x-api-path-slug: v3projectsidaccess-requests-post
      parameters:
      - in: path
        name: id
        description: The project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
  /v3/projects/{id}/access_requests/{user_id}/approve:
    put:
      summary: Put Projects Access Requests User Approve
      description: This feature was introduced in GitLab 8.11.
      operationId: putV3ProjectsIdAccessRequestsUserIdApprove
      x-api-path-slug: v3projectsidaccess-requestsuser-idapprove-put
      parameters:
      - in: formData
        name: access_level
        description: 'A valid access level (defaults: `30`, developer access level)'
      - in: path
        name: id
        description: The project ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
      - User
      - Approve
  /v3/projects/{id}/access_requests/{user_id}:
    delete:
      summary: Delete Projects Access Requests User
      description: This feature was introduced in GitLab 8.11.
      operationId: deleteV3ProjectsIdAccessRequestsUserId
      x-api-path-slug: v3projectsidaccess-requestsuser-id-delete
      parameters:
      - in: path
        name: id
        description: The project ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
      - User