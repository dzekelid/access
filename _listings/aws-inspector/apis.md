---
name: AWS Inspector
x-slug: aws-inspector
description: Amazon Inspector is an automated security assessment service that helps
  improve the security and compliance of applications deployed on AWS. Amazon Inspector
  automatically assesses applications for vulnerabilities or deviations from best
  practices. After performing an assessment, Amazon Inspector produces a detailed
  list of security findings prioritized by level of severity.To help you get started
  quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
  to common security best practices and vulnerability definitions. Examples of built-in
  rules include checking for remote root login being enabled, or vulnerable software
  versions installed. These rules are regularly updated by AWS security researchers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Access
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-inspector/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Inspector API Describe Cross Account Access Role
  x-api-slug: aws-inspector-api
  description: |-
    Describes the IAM role that enables Amazon Inspector to access your AWS
             account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DescribeCrossAccountAccessRole
  tags: Cross Account Access Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-inspector/actiondescribecrossaccountaccessrole-get-openapi.md
- name: AWS Inspector API Register Cross Account Access Role
  x-api-slug: aws-inspector-api
  description: |-
    Registers the IAM role that Amazon Inspector uses to list your EC2 instances at the
             start of the assessment run or when you call the.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=RegisterCrossAccountAccessRole
  tags: Cross Account Access Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-inspector/actionregistercrossaccountaccessrole-get-openapi.md
- name: AWS Inspector API
  x-api-slug: aws-inspector-api
  description: Amazon Inspector is an automated security assessment service that helps
    improve the security and compliance of applications deployed on AWS. Amazon Inspector
    automatically assesses applications for vulnerabilities or deviations from best
    practices. After performing an assessment, Amazon Inspector produces a detailed
    list of security findings prioritized by level of severity.To help you get started
    quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
    to common security best practices and vulnerability definitions. Examples of built-in
    rules include checking for remote root login being enabled, or vulnerable software
    versions installed. These rules are regularly updated by AWS security researchers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/access/master/_listings/aws-inspector/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/inspector/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/inspector/faqs/
- type: x-getting-started
  url: https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
- type: x-partners
  url: https://aws.amazon.com/inspector/partners/
- type: x-pricing
  url: https://aws.amazon.com/inspector/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/inspector/customers/
- type: x-website
  url: https://aws.amazon.com/inspector/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---