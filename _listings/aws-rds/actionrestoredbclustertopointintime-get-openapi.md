---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Restore D B Cluster To Point In Time
  version: 1.0.0
  description: Restores a DB cluster to an arbitrary point in time.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RestoreDBClusterToPointInTime:
    get:
      summary: Restore D B Cluster To Point In Time
      description: Restores a DB cluster to an arbitrary point in time.
      operationId: restoredbclustertopointintime
      x-api-path-slug: actionrestoredbclustertopointintime-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the new DB cluster to be created
        type: string
      - in: query
        name: DBSubnetGroupName
        description: The DB subnet group name to use for the new DB cluster
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier to use when restoring an encrypted DB
          cluster from an encrypted DB cluster
        type: string
      - in: query
        name: OptionGroupName
        description: The name of the option group for the new DB cluster
        type: string
      - in: query
        name: Port
        description: The port number on which the new DB cluster accepts connections
        type: string
      - in: query
        name: RestoreToTime
        description: The date and time to restore the DB cluster to
        type: string
      - in: query
        name: SourceDBClusterIdentifier
        description: The identifier of the source DB cluster from which to restore
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: UseLatestRestorableTime
        description: A value that is set to true to restore the DB cluster to the
          latest       restorable backup time, and false otherwise
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A lst of VPC security groups that the new DB cluster belongs
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
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