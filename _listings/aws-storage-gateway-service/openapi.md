swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 1
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
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
  /?Action=RetrieveTapeRecoveryPoint:
    get:
      summary: Retrieve Tape Recovery Point
      description: Retrieves the recovery point for the specified virtual tape.
      operationId: retrieveTapeRecoveryPoint
      x-api-path-slug: actionretrievetaperecoverypoint-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape for which
          you want to retrieve the         recovery point
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tape Recovery