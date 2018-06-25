---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Access
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of    OAuth 2.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Fetches the details of given access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-get-openapi.md
- name: Apigee Edge Post Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Revokes the specified access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-post-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Deletes the specified access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Accesstokens
  x-api-slug: apigee-edge
  description: Returns a count of all 1.0a access tokens in an orgnization .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens
  tags: Organizations,Oauth1,Accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Gets details of a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-get-openapi.md
- name: Apigee Edge Post Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Revokes a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-post-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Deletes a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens under an organization .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens
  tags: Organizations,Oauth2,Accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/organizationsorg-nameoauth2accesstokens-get-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---