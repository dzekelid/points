swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/spatial-query:
    post:
      summary: |-
        For 'within' operator - find all points within an area.
        For 'nearest' operator - return the nearest point to the one specified.
        For 'lineIntersectsLine' - find all points of intersection between two linestrings.
      description: |-
        'Within' returns GeoGJSON of type FeatureCollection containing all GeoJSON features within the provided polygon.
        'Nearest' returns a FeatureCollection with the longitude and latitude of the nearest point.
        'LineIntersectsLine' returns a FeatureCollection containing all points of intersection as GeoJSON features.
      operationId: within-returns-geogjson-of-type-featurecollection-containing-all-geojson-features-within-the-provide
      x-api-path-slug: v1collectionscollectionnamespatialquery-post
      parameters:
      - in: body
        name: body
        description: For within query - a geojson polygon which we wish to search
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      - in: query
        name: operator
        description: The type of spatial query
      responses:
        200:
          description: OK
      tags:
      - For
      - Within
      - Operator
      - '-'
      - Find
      - ""
      - Points
      - Within
      - Area
      - For
      - Nearest
      - Operator
      - '-'
      - Return
      - Nearest
      - Point
      - To
      - Specified
      - For
      - LineIntersectsLine
      - '-'
      - Find
      - ""
      - Points
      - Of
      - Intersection
      - Between
      - Two
      - Linestrings