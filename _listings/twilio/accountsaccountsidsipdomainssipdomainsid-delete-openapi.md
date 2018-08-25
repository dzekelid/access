---
swagger: "2.0"
x-collection-name: Twilio
x-complete: 0
info:
  title: Twilio Delete Domains IP Access Control List Mappings
  description: Delete a domain. If you have created subdomains of a domain, you will
    not be able to delete the domain until you first delete all subdomains of it.
  termsOfService: https://www.twilio.com/legal/tos
  version: v1
host: api.twilio.com
basePath: /2010-04-01/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}:
    delete:
      summary: Delete Domains IP Access Control List Mappings
      description: Delete a domain. If you have created subdomains of a domain, you
        will not be able to delete the domain until you first delete all subdomains
        of it.
      operationId: delete-a-domain-if-you-have-created-subdomains-of-a-domain-you-will-not-be-able-to-delete-the-domain
      x-api-path-slug: accountsaccountsidsipdomainssipdomainsid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: SipDomainSid
        description: A 34 character string that uniquely identifies the SIP domain
      responses:
        200:
          description: OK
      tags:
      - SIP Domains
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