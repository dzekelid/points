---
swagger: "2.0"
x-collection-name: ConvertAPI
x-complete: 0
info:
  title: Convert API PDF to Power Point
  description: The API for converting PDF documents to PowerPoint presentation files.
    These file formats pdf, pdfa can be converted to pptx.
  version: v1
host: do.convertapi.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Pdf2PowerPoint:
    post:
      summary: PDF to Power Point
      description: The API for converting PDF documents to PowerPoint presentation
        files. These file formats pdf, pdfa can be converted to pptx.
      operationId: pdf2powerpoint
      x-api-path-slug: pdf2powerpoint-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: pdf, pdfa'
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - PDF
      - Power
      - Point
  /PowerPoint2Image:
    post:
      summary: Power Point to Image
      description: The API for converting PowerPoint documents to PDF files and Images.
        These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to png,
        jpg, tif.
      operationId: powerpoint2image
      x-api-path-slug: powerpoint2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: pot, potx, pps, ppsx, ppt, pptx'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Power
      - Point
      - Image
  /PowerPoint2Pdf:
    post:
      summary: Power Point to PDF
      description: The API for converting PowerPoint documents to PDF files and Images.
        These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to pdf,
        pdfa, png, jpg, tif.
      operationId: powerpoint2pdf
      x-api-path-slug: powerpoint2pdf-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: DocumentAuthor
        description: Set the author of the generated Pdf file
      - in: query
        name: DocumentKeywords
        description: Set the keywords of the generated Pdf file
      - in: query
        name: DocumentSubject
        description: Set the subject of the generated Pdf file
      - in: query
        name: DocumentTitle
        description: Set the title of the generated Pdf file
      - in: query
        name: File
        description: 'Supported source file formats: pot, potx, pps, ppsx, ppt, pptx'
      - in: query
        name: OutputFormat
        description: Supported output file formats pdf, pdfa, png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Power
      - Point
      - PDF
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