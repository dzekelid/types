swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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