---
swagger: "2.0"
x-collection-name: BC Geographical Names
x-complete: 0
info:
  title: Geo Mark Web Service Gets a single spatial point representative of the geomark.
  description: The geomark point resource returns a single spatial feature with a
    single Point and the geomark attribution.  The point geometry will be created
    from the first geometry part of the Geomark. Point geomarks will return the first
    Point part in the geomark.  LineString geomarks will return the first coordinate
    of the first LineString part in the geomark. Polygon geomarks will return the
    centroid or another point inside the first Polygon part in the geomark. The geometry
    and attribution can be downloaded as a spatial download file format in a supported
    coordinate system. The download files can then be used in a desktop GIS application
    (e.g. ArcMap), Google Earth or a web mapping application.
  termsOfService: http://www2.gov.bc.ca/gov/content/governments/about-the-bc-government/databc/open-data/api-terms-of-use-for-ogl-information
  contact:
    name: Data BC
    url: http://data.gov.bc.ca/
    email: DataBCBA@gov.bc.ca
  version: 4.1.2
host: apps.gov.bc.ca
basePath: /pub/geomark
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /geomarks/{geomarkId}/point.{fileFormatExtension}:
    get:
      summary: Gets a single spatial point representative of the geomark.
      description: The geomark point resource returns a single spatial feature with
        a single Point and the geomark attribution.  The point geometry will be created
        from the first geometry part of the Geomark. Point geomarks will return the
        first Point part in the geomark.  LineString geomarks will return the first
        coordinate of the first LineString part in the geomark. Polygon geomarks will
        return the centroid or another point inside the first Polygon part in the
        geomark. The geometry and attribution can be downloaded as a spatial download
        file format in a supported coordinate system. The download files can then
        be used in a desktop GIS application (e.g. ArcMap), Google Earth or a web
        mapping application.
      operationId: the-geomark-point-resource-returns-a-single-spatial-feature-with-a-single-point-and-the-geomark-attr
      x-api-path-slug: geomarksgeomarkidpoint-fileformatextension-get
      parameters:
      - in: path
        name: fileFormatExtension
        description: The file format name extension used to represent the geomark
          download
      - in: path
        name: geomarkId
        description: The unique identifier for the geomark (e
      - in: query
        name: srid
        description: The srid of the coordinate system the geometry should be converted
          to
      responses:
        200:
          description: OK
      tags:
      - Geomarks
      - GeomarkId
      - Point
      - FileFormatExtension
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