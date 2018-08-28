---
swagger: "2.0"
x-collection-name: ATTOM
x-complete: 0
info:
  title: Attom Data Solutions API Returns POIs based on point.
  description: This search returns a list of POI in proximity to a latitude/longitude.
  version: 1.0.0
host: search.onboard-apis.com
basePath: /communityapi/v2.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /school/snapshot:
    get:
      summary: Return all schools within a defined radius from a point.
      description: Search for all schools that are located within a given radius around
        a given latitude and longitude.
      operationId: propertySchoolSnapshot
      x-api-path-slug: schoolsnapshot-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: filetypetext
        description: The type of school (public, private, or catholic can be selected)
      - in: query
        name: latitude
        description: The property latitude coordinate
      - in: query
        name: longitude
        description: The property longitude coordinate
      - in: query
        name: radius
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Schools
      - Within
      - Defined
      - Radius
      - From
      - Point
  /hierarchy/lookup:
    get:
      summary: Returns all boundaries a point falls within.
      description: This method allows you to pass a latitude and longitude point and
        geo type to retrieve a list of geographies that point falls within. Required
        input is a valid WKT (Well Known Text) point.
      operationId: getAreaHierarchyLookup
      x-api-path-slug: hierarchylookup-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: geoType
        description: known Geo Type
      - in: query
        name: latitude
        description: The property latitude coordinate
      - in: query
        name: longitude
        description: The property longitude coordinate
      - in: query
        name: WKTString
        description: WKTString parameters
      responses:
        200:
          description: OK
      tags:
      - Returns
      - ""
      - Boundaries
      - Point
      - Falls
      - Within
  /poi/point:
    get:
      summary: Returns POIs based on point.
      description: This search returns a list of POI in proximity to a latitude/longitude.
      operationId: getPOISearchPoint
      x-api-path-slug: poipoint-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: BusinessCategory
        description: This is Business Category as per Lookup separated by pipe |
      - in: query
        name: Point
        description: This is the Point value
      - in: query
        name: RecordLimit
        description: This is RecordLimit
      - in: query
        name: SearchDistance
        description: This is SearchDistance
      - in: query
        name: Sort
        description: This is for Sortable Columns
      responses:
        200:
          description: OK
      tags:
      - Returns
      - POIs
      - Based
      - "On"
      - Point
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