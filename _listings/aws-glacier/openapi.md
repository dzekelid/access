---
swagger: "2.0"
x-collection-name: AWS Glacier
x-complete: 1
info:
  title: AWS Glacier API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{AccountId}/vaults/{vaultName}/access-policy:
    delete:
      summary: Delete  Vault  Access  Policy
      description: "DescriptionThis operation deletes the access policy associated
        with the specified vault. The\n\t\t\toperation is eventually consistent&#8212;that
        is, it might take some time for Amazon Glacier to\n\t\t\tcompletely remove
        the access policy, and you might still see the effect of the policy\n\t\t\tfor
        a short time after you send the delete request. This operation is idempotent.
        You can invoke delete multiple times, even if there is\n\t\t\tno policy associated
        with the vault. For more information about vault access policies,\n\t\t\tsee
        Amazon Glacier Access Control with Vault Access Policies.RequestsTo delete
        the current vault access policy, send an HTTP DELETE request to\n\t\t\tthe
        URI of the vault's access-policy subresource."
      operationId: "Delete Vault Access Policy (DELETE\n\t\taccess-policy)"
      x-api-path-slug: accountidvaultsvaultnameaccesspolicy-delete
      responses:
        200:
          description: OK
      tags:
      - Vault Access Policies
    get:
      summary: Get  Vault  Access  Policy
      description: "DescriptionThis operation retrieves the access-policy subresource
        set on the\n\t\t\tvault&#8212;for more information on setting this subresource,
        see Set Vault Access Policy (PUT access-policy). If\n\t\t\tthere is no access
        policy set on the vault, the operation returns a 404 Not\n\t\t\t\tfound error.
        For more information about vault access policies, see Amazon Glacier Access
        Control with Vault Access Policies.RequestsTo return the current vault access
        policy, send an HTTP GET request to\n\t\t\tthe URI of the vault's access-policy
        subresource."
      operationId: Get Vault Access Policy (GET access-policy)
      x-api-path-slug: accountidvaultsvaultnameaccesspolicy-get
      parameters:
      - in: query
        name: Policy
        description: The vault access policy as a JSON string, which uses \ as an
          escape character
        type: string
      responses:
        200:
          description: OK
      tags:
      - Vault Access Policies
    put:
      summary: Set  Vault  Access  Policy
      description: "DescriptionThis operation configures an access policy for a vault
        and will overwrite an existing\n\t\t\tpolicy. To configure a vault access
        policy, send a PUT request to the\n\t\t\t\taccess-policy subresource of the
        vault. You can set one access policy per vault\n\t\t\tand the policy can be
        up to 20 KB in size. For more information about vault access\n\t\t\tpolicies,
        see Amazon Glacier Access Control with Vault Access Policies. Requests"
      operationId: Set Vault Access Policy (PUT access-policy)
      x-api-path-slug: accountidvaultsvaultnameaccesspolicy-put
      parameters:
      - in: query
        name: Policy
        description: The vault access policy as a JSON string, which uses \ as an
          escape character
        type: string
      responses:
        200:
          description: OK
      tags:
      - Vault Access Policies
---