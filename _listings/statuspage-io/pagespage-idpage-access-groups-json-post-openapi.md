---
swagger: "2.0"
x-collection-name: StatusPage.io
x-complete: 0
info:
  title: StatusPage.io Create a group that will define what and who can view elements
    of your status page
  version: 1.0.0
  description: Create a group that will define what and who can view elements of your
    status page
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/[page_id]/components/[component_id].json:
    patch:
      summary: Update a component
      description: Update a component
      operationId: update-a-component
      x-api-path-slug: pagespage-idcomponentscomponent-id-json-patch
      parameters:
      - in: query
        name: component[description]
        description: The description of the component
        type: string
      - in: query
        name: component[name]
        description: The name of the component
        type: string
      - in: query
        name: component[status]
        description: The status, one of operational|degraded_performance|partial_outage|major_outage
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Group
  /pages/[page_id]/page_access_users.json:
    get:
      summary: Retrieve a list of users
      description: Retrieve a list of users
      operationId: retrieve-a-list-of-users
      x-api-path-slug: pagespage-idpage-access-users-json-get
      parameters:
      - in: query
        name: email
        description: Filter the returned list of users by email address (users must
          have assigned email addresses)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    post:
      summary: Create a user who can view your status page
      description: Create a user who can view your status page
      operationId: create-a-user-who-can-view-your-status-page
      x-api-path-slug: pagespage-idpage-access-users-json-post
      parameters:
      - in: query
        name: page_access_user[component_ids][]
        description: Array of component ids that the created user will ba able to
          view
        type: string
      - in: query
        name: page_access_user[email]
        description: The email for StatusPage to use to communicate with the user
          (required if StatusPage manages passwords for you)
        type: string
      - in: query
        name: page_access_user[external_login]
        description: A concatenated (and possibly hashed) string of login parameters,
          organized alphabetically by field name
        type: string
      - in: query
        name: page_access_user[metric_ids][]
        description: Array of metric ids that the created user will ba able to view
        type: string
      - in: query
        name: page_access_user[page_access_group_ids][]
        description: Array of PageAccessGroups (identified by code) that the created
          user will be a member of
        type: string
      - in: query
        name: page_access_user[subscribe_to_components]
        description: A value of true will subscribe the user to notifications for
          incidents associated with components they can see, this value is optional
          and defaults to false
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
  /pages/[page_id]/page_access_users/[page_access_user_id].json:
    patch:
      summary: Change information for a user who can view your status page
      description: Change information for a user who can view your status page
      operationId: change-information-for-a-user-who-can-view-your-status-page
      x-api-path-slug: pagespage-idpage-access-userspage-access-user-id-json-patch
      parameters:
      - in: query
        name: page_access_user[component_ids][]
        description: Array of component ids that the created user will ba able to
          view
        type: string
      - in: query
        name: page_access_user[email]
        description: The email for StatusPage to use to communicate with the user
          (required if StatusPage manages passwords for you)
        type: string
      - in: query
        name: page_access_user[external_login]
        description: A concatenated (and possibly hashed) string of login parameters,
          organized alphabetically by field name
        type: string
      - in: query
        name: page_access_user[metric_ids][]
        description: Array of metric ids that the created user will ba able to view
        type: string
      - in: query
        name: page_access_user[page_access_group_ids][]
        description: Array of PageAccessGroups (identified by code) that the created
          user will be a member of
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    delete:
      summary: Delete a user who could access your status page
      description: Delete a user who could access your status page
      operationId: delete-a-user-who-could-access-your-status-page
      x-api-path-slug: pagespage-idpage-access-userspage-access-user-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
  /pages/[page_id]/page_access_users/[page_access_user_id]/components.json:
    post:
      summary: Assign components to a page access user (overwrites existing components)
      description: Assign components to a page access user (overwrites existing components)
      operationId: assign-components-to-a-page-access-user-overwrites-existing-components
      x-api-path-slug: pagespage-idpage-access-userspage-access-user-idcomponents-json-post
      parameters:
      - in: query
        name: component_ids[]
        description: Array of component ids that the user will ba able to view
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    patch:
      summary: Assign components to a page access user (adds new components to a user)
      description: Assign components to a page access user (adds new components to
        a user)
      operationId: assign-components-to-a-page-access-user-adds-new-components-to-a-user
      x-api-path-slug: pagespage-idpage-access-userspage-access-user-idcomponents-json-patch
      parameters:
      - in: query
        name: component_ids[]
        description: Array of component ids that the user will ba able to view
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    delete:
      summary: Remove all components from a page access user
      description: Remove all components from a page access user
      operationId: remove-all-components-from-a-page-access-user
      x-api-path-slug: pagespage-idpage-access-userspage-access-user-idcomponents-json-delete
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
  /pages/[page_id]/components/[component_id]/page_access_users.json:
    post:
      summary: Assign page access users to a component
      description: Assign page access users to a component
      operationId: assign-page-access-users-to-a-component
      x-api-path-slug: pagespage-idcomponentscomponent-idpage-access-users-json-post
      parameters:
      - in: query
        name: page_access_user_ids[]
        description: Array of page access user ids for users that can access the referenced
          component
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    delete:
      summary: Remove a component from all page access users
      description: Remove a component from all page access users
      operationId: remove-a-component-from-all-page-access-users
      x-api-path-slug: pagespage-idcomponentscomponent-idpage-access-users-json-delete
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
  /pages/[page_id]/page_access_groups.json:
    get:
      summary: Retrieve a list of groups
      description: Retrieve a list of groups
      operationId: retrieve-a-list-of-groups
      x-api-path-slug: pagespage-idpage-access-groups-json-get
      responses:
        200:
          description: OK
      tags:
      - Page Access Group
    post:
      summary: Create a group that will define what and who can view elements of your
        status page
      description: Create a group that will define what and who can view elements
        of your status page
      operationId: create-a-group-that-will-define-what-and-who-can-view-elements-of-your-status-page
      x-api-path-slug: pagespage-idpage-access-groups-json-post
      parameters:
      - in: query
        name: page_access_group[component_ids][]
        description: Array of component ids that the created group will be able to
          view
        type: string
      - in: query
        name: page_access_group[external_identifier]
        description: A unique string that can be used to associate this group with
          an external group (optional)
        type: string
      - in: query
        name: page_access_group[metric_ids][]
        description: Array of metric ids that the created group will be able to view
        type: string
      - in: query
        name: page_access_group[name]
        description: The name the group (required)
        type: string
      - in: query
        name: page_access_group[page_access_user_ids][]
        description: Array of Page Access User ids that the created group contain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Group
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