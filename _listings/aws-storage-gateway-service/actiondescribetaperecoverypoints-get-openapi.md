---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 0
info:
  title: AWS Storage Gateway Service API Describe Tape Recovery Points
  version: 1.0.0
  description: |-
    Returns a list of virtual tape recovery points that are available for the specified
             gateway-VTL.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeTapeRecoveryPoints:
    get:
      summary: Describe Tape Recovery Points
      description: |-
        Returns a list of virtual tape recovery points that are available for the specified
                 gateway-VTL.
      operationId: describeTapeRecoveryPoints
      x-api-path-slug: actiondescribetaperecoverypoints-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: Limit
        description: Specifies that the number of virtual tape recovery points that
          are described be         limited to the specified number
        type: string
      - in: query
        name: Marker
        description: An opaque string that indicates the position at which to begin
          describing the virtual         tape recovery points
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tape Recovery Points
  /?Action=ListVolumeRecoveryPoints:
    get:
      summary: List Volume Recovery Points
      description: Lists the recovery points for a specified gateway.
      operationId: listVolumeRecoveryPoints
      x-api-path-slug: actionlistvolumerecoverypoints-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume Recovery
  /?Action=CreateSnapshotFromVolumeRecoveryPoint:
    get:
      summary: Create Snapshot From Volume Recovery Point
      description: Initiates a snapshot of a gateway from a volume recovery point.
      operationId: createSnapshotFromVolumeRecoveryPoint
      x-api-path-slug: actioncreatesnapshotfromvolumerecoverypoint-get
      parameters:
      - in: query
        name: SnapshotDescription
        description: 'Type: String'
        type: string
      - in: query
        name: VolumeARN
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
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