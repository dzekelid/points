---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Line  Stop Points
  description: Gets a list of the stations that serve the given line id.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Line/{id}/StopPoints:
    get:
      summary: Line  Stop Points
      description: Gets a list of the stations that serve the given line id.
      operationId: Line_StopPoints
      x-api-path-slug: lineidstoppoints-get
      parameters:
      - in: path
        name: id
        description: A single line id e
      - in: query
        name: tflOperatedNationalRailStationsOnly
        description: If the national-rail line is requested, this flag will filter
          the national rail stations so that only those operated by TfL are returned
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Stop
      - Points
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