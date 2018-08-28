---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Points
  description: List points Retrieve a list of chartpoints objects.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/worksheets(&lt;id|name&gt;)/charts(&lt;name&gt;)/series(&lt;undefined&gt;)/points:
    get:
      summary: List Points
      description: List points Retrieve a list of chartpoints objects.
      operationId: ListPoints
      x-api-path-slug: workbookworksheetsltidnamegtchartsltnamegtseriesltundefinedgtpoints-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
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