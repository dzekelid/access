---
name: AWS Glacier
x-slug: aws-glacier
description: Amazon Glacier is a secure, durable, and extremely low-cost cloud storage
  service for data archiving and long-term backup. Customers can reliably store large
  or small amounts of data for as little as $0.004 per gigabyte per month, a significant
  savings compared to on-premises solutions. To keep costs low yet suitable for varying
  retrieval needs, Amazon Glacier provides three options for access to archives, from
  a few minutes to several hours.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonGlacier.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Access
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-glacier/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon Glacier API Delete  Vault  Access  Policy
  x-api-slug: amazon-glacier-api
  description: "DescriptionThis operation deletes the access policy associated with
    the specified vault. The\n\t\t\toperation is eventually consistent&#8212;that
    is, it might take some time for Amazon Glacier to\n\t\t\tcompletely remove the
    access policy, and you might still see the effect of the policy\n\t\t\tfor a short
    time after you send the delete request. This operation is idempotent. You can
    invoke delete multiple times, even if there is\n\t\t\tno policy associated with
    the vault. For more information about vault access policies,\n\t\t\tsee Amazon
    Glacier Access Control with Vault Access Policies.RequestsTo delete the current
    vault access policy, send an HTTP DELETE request to\n\t\t\tthe URI of the vault's
    access-policy subresource."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonGlacier.png
  humanURL: https://aws.amazon.com/glacier/
  baseURL: ://///{AccountId}/vaults/{vaultName}/access-policy
  tags: Vault Access Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-glacier/accountidvaultsvaultnameaccesspolicy-delete-openapi.md
- name: Amazon Glacier API Get  Vault  Access  Policy
  x-api-slug: amazon-glacier-api
  description: "DescriptionThis operation retrieves the access-policy subresource
    set on the\n\t\t\tvault&#8212;for more information on setting this subresource,
    see Set Vault Access Policy (PUT access-policy). If\n\t\t\tthere is no access
    policy set on the vault, the operation returns a 404 Not\n\t\t\t\tfound error.
    For more information about vault access policies, see Amazon Glacier Access Control
    with Vault Access Policies.RequestsTo return the current vault access policy,
    send an HTTP GET request to\n\t\t\tthe URI of the vault's access-policy subresource."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonGlacier.png
  humanURL: https://aws.amazon.com/glacier/
  baseURL: ://///{AccountId}/vaults/{vaultName}/access-policy
  tags: Vault Access Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-glacier/accountidvaultsvaultnameaccesspolicy-get-openapi.md
- name: Amazon Glacier API Set  Vault  Access  Policy
  x-api-slug: amazon-glacier-api
  description: "DescriptionThis operation configures an access policy for a vault
    and will overwrite an existing\n\t\t\tpolicy. To configure a vault access policy,
    send a PUT request to the\n\t\t\t\taccess-policy subresource of the vault. You
    can set one access policy per vault\n\t\t\tand the policy can be up to 20 KB in
    size. For more information about vault access\n\t\t\tpolicies, see Amazon Glacier
    Access Control with Vault Access Policies. Requests"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonGlacier.png
  humanURL: https://aws.amazon.com/glacier/
  baseURL: ://///{AccountId}/vaults/{vaultName}/access-policy
  tags: Vault Access Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-glacier/accountidvaultsvaultnameaccesspolicy-put-openapi.md
- name: Amazon Glacier API
  x-api-slug: amazon-glacier-api
  description: Amazon Glacier is a secure, durable, and extremely low-cost cloud storage
    service for data archiving and long-term backup. Customers can reliably store
    large or small amounts of data for as little as $0.004 per gigabyte per month,
    a significant savings compared to on-premises solutions. To keep costs low yet
    suitable for varying retrieval needs, Amazon Glacier provides three options for
    access to archives, from a few minutes to several hours.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonGlacier.png
  humanURL: https://aws.amazon.com/glacier/
  baseURL: :///
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-glacier/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-Glacier/
- type: x-documentation
  url: http://docs.aws.amazon.com/amazonglacier/latest/dev/amazon-glacier-api.html
- type: x-faq
  url: https://aws.amazon.com/glacier/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=140
- type: x-getting-started
  url: https://aws.amazon.com/glacier/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/glacier/pricing/
- type: x-website
  url: https://aws.amazon.com/glacier/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---