---
swagger: "2.0"
x-collection-name: Twilio
x-complete: 0
info:
  title: Twilio Get SIP IP Access Control List
  description: Return a paged list of all IpAccessControlLists under this account.
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
  /Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{IpAddressSid}:
    delete:
      summary: Delete SIP IP Access Control List IP Address
      description: Deletes an IP address entry from the list.
      operationId: deletes-an-ip-address-entry-from-the-list
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      - in: path
        name: IpAddressSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
    get:
      summary: Get SIP IP Access Control List IP Address
      description: Return a single IP Address resource.
      operationId: return-a-single-ip-address-resource
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      - in: path
        name: IpAddressSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
    post:
      summary: Add SIP IP Access Control List IP Address
      description: Change the description or IP address of a given IpAddress instance
        resource
      operationId: change-the-description-or-ip-address-of-a-given-ipaddress-instance-resource
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      - in: path
        name: IpAddressSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
  /Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses:
    get:
      summary: Get SIP IP Access Control List IP Address
      description: List the IP Addresses contained in this list.
      operationId: list-the-ip-addresses-contained-in-this-list
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
    post:
      summary: Add SIP IP Access Control List IP Address
      description: Add an IP Address to the list with a description.
      operationId: add-an-ip-address-to-the-list-with-a-description
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
  /Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}:
    delete:
      summary: Delete SIP IP Access Control List IP Address
      description: Delete an IpAccessControlList from your account. It can only be
        deleted if no domains are mapped to it. If you attempt to delete one that
        is mapped to a domain, you will receive an error.
      operationId: delete-an-ipaccesscontrollist-from-your-account-it-can-only-be-deleted-if-no-domains-are-mapped-to-i
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
    get:
      summary: Get SIP IP Access Control List IP Address
      description: Return a specific IpAccessControlList resource.
      operationId: return-a-specific-ipaccesscontrollist-resource
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
    post:
      summary: Add SIP IP Access Control List IP Address
      description: Rename an IpAccessControlList.
      operationId: rename-an-ipaccesscontrollist
      x-api-path-slug: accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: IpAccessControlListSid
        description: A 34 character string that uniquely identifies the SIP IP access
          control list
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
  /Accounts/{AccountSid}/SIP/IpAccessControlLists:
    get:
      summary: Get SIP IP Access Control List
      description: Return a paged list of all IpAccessControlLists under this account.
      operationId: return-a-paged-list-of-all-ipaccesscontrollists-under-this-account
      x-api-path-slug: accountsaccountsidsipipaccesscontrollists-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - SIP IP Access Control Lists
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