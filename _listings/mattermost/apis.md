---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Access
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Create a user access token
  x-api-slug: mattermost-api
  description: |-
    Generate a user access token that can be used to authenticate with the Mattermost REST API.

    __Minimum server version__: 4.1

    ##### Permissions
    Must have `create_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/tokens
  tags: User,Access,Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/usersuser-idtokens-post-openapi.md
- name: Mattermost API Get user access tokens
  x-api-slug: mattermost-api
  description: |-
    Get a list of user access tokens for a user. Does not include the actual authentication tokens. Use query paremeters for paging.

    __Minimum server version__: 4.1

    ##### Permissions
    Must have `read_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/tokens
  tags: User,Access,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/usersuser-idtokens-get-openapi.md
- name: Mattermost API Get user access tokens
  x-api-slug: mattermost-api
  description: |-
    Get a page of user access tokens for users on the system. Does not include the actual authentication tokens. Use query parameters for paging.

    __Minimum server version__: 4.7

    ##### Permissions
    Must have `manage_system` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/tokens
  tags: User,Access,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/userstokens-get-openapi.md
- name: Mattermost API Revoke a user access token
  x-api-slug: mattermost-api
  description: |-
    Revoke a user access token and delete any sessions using the token.

    __Minimum server version__: 4.1

    ##### Permissions
    Must have `revoke_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/tokens/revoke
  tags: Revoke,User,Access,Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/userstokensrevoke-post-openapi.md
- name: Mattermost API Get a user access token
  x-api-slug: mattermost-api
  description: |-
    Get a user access token. Does not include the actual authentication token.

    __Minimum server version__: 4.1

    ##### Permissions
    Must have `read_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/tokens/{token_id}
  tags: User,Access,Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/userstokenstoken-id-get-openapi.md
- name: Mattermost API Disable personal access token
  x-api-slug: mattermost-api
  description: |-
    Disable a personal access token and delete any sessions using the token. The token can be re-enabled using `/users/tokens/enable`.

    __Minimum server version__: 4.4

    ##### Permissions
    Must have `revoke_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/tokens/disable
  tags: Disable,Personal,Access,Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/userstokensdisable-post-openapi.md
- name: Mattermost API Enable personal access token
  x-api-slug: mattermost-api
  description: |-
    Re-enable a personal access token that has been disabled.

    __Minimum server version__: 4.4

    ##### Permissions
    Must have `create_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/tokens/enable
  tags: Enable,Personal,Access,Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/userstokensenable-post-openapi.md
- name: Mattermost API
  x-api-slug: mattermost-api
  description: Open source, private cloud Slack-alternative, Workplace messaging for
    web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
    configurable, and scalable from teams to the enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/mattermost/openapi.md
x-common:
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---