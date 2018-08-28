---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Art Photo Type
  version: 1.0.0
  description: Post art photo type.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/statistics/{type}:
    get:
      summary: Get Admin Statistics Type
      description: Get admin statistics type.
      operationId: getApiV1AdminStatisticsType
      x-api-path-slug: apiv1adminstatisticstype-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Statistics
      - Type
  /api/v1/art/photo/{type}:
    post:
      summary: Post Art Photo Type
      description: Post art photo type.
      operationId: postApiV1ArtPhotoType
      x-api-path-slug: apiv1artphototype-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Art
      - Photo
      - Type
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