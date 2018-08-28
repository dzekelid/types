---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API association types (2.x only)
  description: Association types (2.x only).
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/association-types:
    get:
      summary: association types (2.x only)
      description: Association types (2.x only).
      operationId: RestV1AssociationTypesGet
      x-api-path-slug: restv1associationtypes-get
      responses:
        200:
          description: OK
      tags:
      - Association
      - Types
      - (2
      - X
      - Only)
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