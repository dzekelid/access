---
name: StatusPage.io
x-slug: statuspage-io
description: StatusPage.io is the best way for web infrastructure, developer API,
  and SaaS companies to get set up with their very own status page in minutes
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
x-kinRank: "8"
x-alexaRank: "34645"
tags: Access
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/apis.md
specificationVersion: "0.14"
apis:
- name: StatusPage.io Update a component
  x-api-slug: statuspage-io
  description: Update a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-patch-openapi.md
- name: StatusPage.io Retrieve a list of users
  x-api-slug: statuspage-io
  description: Retrieve a list of users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-users-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-users-json-get-openapi.md
- name: StatusPage.io Create a user who can view your status page
  x-api-slug: statuspage-io
  description: Create a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-users-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-users-json-post-openapi.md
- name: StatusPage.io Change information for a user who can view your status page
  x-api-slug: statuspage-io
  description: Change information for a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-patch-openapi.md
- name: StatusPage.io Delete a user who could access your status page
  x-api-slug: statuspage-io
  description: Delete a user who could access your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-delete-openapi.md
- name: StatusPage.io Assign components to a page access user (overwrites existing
    components)
  x-api-slug: statuspage-io
  description: Assign components to a page access user (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-post-openapi.md
- name: StatusPage.io Assign components to a page access user (adds new components
    to a user)
  x-api-slug: statuspage-io
  description: Assign components to a page access user (adds new components to a user)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-patch-openapi.md
- name: StatusPage.io Remove all components from a page access user
  x-api-slug: statuspage-io
  description: Remove all components from a page access user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-delete-openapi.md
- name: StatusPage.io Assign page access users to a component
  x-api-slug: statuspage-io
  description: Assign page access users to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-post-openapi.md
- name: StatusPage.io Remove a component from all page access users
  x-api-slug: statuspage-io
  description: Remove a component from all page access users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-delete-openapi.md
- name: StatusPage.io Retrieve a list of groups
  x-api-slug: statuspage-io
  description: Retrieve a list of groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-get-openapi.md
- name: StatusPage.io Create a group that will define what and who can view elements
    of your status page
  x-api-slug: statuspage-io
  description: Create a group that will define what and who can view elements of your
    status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-post-openapi.md
- name: StatusPage.io Change information for a group
  x-api-slug: statuspage-io
  description: Change information for a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-patch-openapi.md
- name: StatusPage.io Delete a group
  x-api-slug: statuspage-io
  description: Delete a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-delete-openapi.md
- name: StatusPage.io Assign components to a page access group (overwrites existing
    components)
  x-api-slug: statuspage-io
  description: Assign components to a page access group (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-post-openapi.md
- name: StatusPage.io Assign components to a page access group (adds new components
    to a group)
  x-api-slug: statuspage-io
  description: Assign components to a page access group (adds new components to a
    group)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-patch-openapi.md
- name: StatusPage.io Remove all components from a page access group
  x-api-slug: statuspage-io
  description: Remove all components from a page access group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-delete-openapi.md
- name: StatusPage.io Assign page access groups to a component
  x-api-slug: statuspage-io
  description: Assign page access groups to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-post-openapi.md
- name: StatusPage.io Remove a component from all page access groups
  x-api-slug: statuspage-io
  description: Remove a component from all page access groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-delete-openapi.md
- name: StatusPage.io
  x-api-slug: statuspage-io
  description: StatusPage.io is the best way for web infrastructure, developer API,
    and SaaS companies to get set up with their very own status page in minutes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https:///
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/statuspage-io/openapi.md
x-common:
- type: x-authentication
  url: http://doers.statuspage.io/api/authentication/
- type: x-blog
  url: http://blog.statuspage.io
- type: x-blog-rss
  url: http://blog.statuspage.io/posts.rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/statuspage
- type: x-developer
  url: http://doers.statuspage.io/
- type: x-email
  url: hi@statuspage.io
- type: x-github
  url: https://github.com/statuspage
- type: x-pricing
  url: https://www.statuspage.io/pricing
- type: x-privacy
  url: https://www.statuspage.io/privacy-policy
- type: x-security
  url: https://www.statuspage.io/security
- type: x-status
  url: http://metastatuspage.com/
- type: x-terms-of-service
  url: https://www.statuspage.io/terms-of-service
- type: x-twitter
  url: https://twitter.com/statuspageio
- type: x-website
  url: https://www.statuspage.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---