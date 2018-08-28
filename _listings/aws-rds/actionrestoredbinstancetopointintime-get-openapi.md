---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Restore D B Instance To Point In Time
  version: 1.0.0
  description: Restores a DB instance to an arbitrary point in time.
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
  /?Action=RestoreDBInstanceToPointInTime:
    get:
      summary: Restore D B Instance To Point In Time
      description: Restores a DB instance to an arbitrary point in time.
      operationId: restoredbinstancetopointintime
      x-api-path-slug: actionrestoredbinstancetopointintime-get
      parameters:
      - in: query
        name: AutoMinorVersionUpgrade
        description: Indicates that minor version upgrades will be applied automatically
          to the DB instance during the maintenance window
        type: string
      - in: query
        name: AvailabilityZone
        description: The EC2 Availability Zone that the database instance will be
          created in
        type: string
      - in: query
        name: CopyTagsToSnapshot
        description: True to copy all tags from the restored DB instance to snapshots
          of the DB instance; otherwise false
        type: string
      - in: query
        name: DBInstanceClass
        description: The compute and memory capacity of the Amazon RDS DB instance
        type: string
      - in: query
        name: DBName
        description: The database name for the restored DB instance
        type: string
      - in: query
        name: DBSubnetGroupName
        description: The DB subnet group name to use for the new instance
        type: string
      - in: query
        name: Domain
        description: Specify the Active Directory Domain to restore the instance in
        type: string
      - in: query
        name: DomainIAMRoleName
        description: Specify the name of the IAM role to be used when making API calls
          to the Directory Service
        type: string
      - in: query
        name: Engine
        description: The database engine to use for the new instance
        type: string
      - in: query
        name: Iops
        description: The amount of Provisioned IOPS (input/output operations per second)
          to be initially allocated for the DB instance
        type: string
      - in: query
        name: LicenseModel
        description: License model information for the restored DB instance
        type: string
      - in: query
        name: MultiAZ
        description: Specifies if the DB instance is a Multi-AZ deployment
        type: string
      - in: query
        name: OptionGroupName
        description: The name of the option group to be used for the restored DB instance
        type: string
      - in: query
        name: Port
        description: The port number on which the database accepts connections
        type: string
      - in: query
        name: PubliclyAccessible
        description: Specifies the accessibility options for the DB instance
        type: string
      - in: query
        name: RestoreTime
        description: The date and time to restore from
        type: string
      - in: query
        name: SourceDBInstanceIdentifier
        description: The identifier of the source DB instance from which to restore
        type: string
      - in: query
        name: StorageType
        description: Specifies the storage type to be associated with the DB instance
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBInstanceIdentifier
        description: The name of the new database instance to be created
        type: string
      - in: query
        name: TdeCredentialArn
        description: The ARN from the Key Store with which to associate the instance
          for TDE encryption
        type: string
      - in: query
        name: TdeCredentialPassword
        description: The password for the given ARN from the Key Store in order to
          access the device
        type: string
      - in: query
        name: UseLatestRestorableTime
        description: Specifies whether (true) or not (false) the        DB instance
          is restored from the latest backup time
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
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