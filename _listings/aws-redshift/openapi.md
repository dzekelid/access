---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AuthorizeSnapshotAccess:
    get:
      summary: Authorize Snapshot Access
      description: |-
        Authorizes the specified AWS customer account to restore the specified
                    snapshot.
      operationId: authorizeSnapshotAccess
      x-api-path-slug: actionauthorizesnapshotaccess-get
      parameters:
      - in: query
        name: AccountWithRestoreAccess
        description: The identifier of the AWS customer account authorized to restore
          the specified            snapshot
        type: string
      - in: query
        name: SnapshotClusterIdentifier
        description: The identifier of the cluster the snapshot was created from
        type: string
      - in: query
        name: SnapshotIdentifier
        description: The identifier of the snapshot the account is authorized to restore
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=ModifyClusterIamRoles:
    get:
      summary: Modify Cluster Iam Roles
      description: |-
        Modifies the list of AWS Identity and Access Management (IAM) roles that can be
                    used by the cluster to access other AWS services.
      operationId: modifyClusterIamRoles
      x-api-path-slug: actionmodifyclusteriamroles-get
      parameters:
      - in: query
        name: AddIamRoles.IamRoleArn.N
        description: Zero or more IAM roles to associate with the cluster
        type: string
      - in: query
        name: ClusterIdentifier
        description: The unique identifier of the cluster for which you want to associate
          or            disassociate IAM roles
        type: string
      - in: query
        name: RemoveIamRoles.IamRoleArn.N
        description: Zero or more IAM roles in ARN format to disassociate from the
          cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster IAM Roles
  /?Action=RevokeSnapshotAccess:
    get:
      summary: Revoke Snapshot Access
      description: |-
        Removes the ability of the specified AWS customer account to restore the specified
                    snapshot.
      operationId: revokeSnapshotAccess
      x-api-path-slug: actionrevokesnapshotaccess-get
      parameters:
      - in: query
        name: AccountWithRestoreAccess
        description: The identifier of the AWS customer account that can no longer
          restore the specified            snapshot
        type: string
      - in: query
        name: SnapshotClusterIdentifier
        description: The identifier of the cluster the snapshot was created from
        type: string
      - in: query
        name: SnapshotIdentifier
        description: The identifier of the snapshot that the account can no longer
          access
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
---