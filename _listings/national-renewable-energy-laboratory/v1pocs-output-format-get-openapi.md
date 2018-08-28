---
swagger: "2.0"
x-collection-name: National Renewable Energy Laboratory
x-complete: 0
info:
  title: Transportation Laws and Incentives Get the points of contact for a given
    jurisdiction.
  description: Get the points of contact for a given jurisdiction..
  version: 0.1.0
host: developer.nrel.gov
basePath: /api/transportation-incentives-laws
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/pocs.{output_format}:
    get:
      summary: Get the points of contact for a given jurisdiction.
      description: Get the points of contact for a given jurisdiction..
      operationId: v1.pocs.output_format.get
      x-api-path-slug: v1pocs-output-format-get
      parameters:
      - in: query
        name: jurisdiction
        description: Return the points of contact for the given Jurisdiction
      - in: path
        name: output_format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Points
      - Of
      - Contacta
      - Given
      - Jurisdiction
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