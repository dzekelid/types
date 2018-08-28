---
swagger: "2.0"
x-collection-name: HHS Media Services
x-complete: 0
info:
  title: HHS Media Services Get MediaTypes
  description: Returns the list of available MediaTypes.
  termsOfService: http://www.hhs.gov/web/socialmedia/policies/tos.html#ready
  version: "2"
host: api.digitalmedia.hhs.gov
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /resources/mediaTypes.json:
    get:
      summary: Get MediaTypes
      description: Returns the list of available MediaTypes.
      operationId: getMediaTypes
      x-api-path-slug: resourcesmediatypes-json-get
      responses:
        200:
          description: OK
      tags:
      - Resources
      - MediaTypes
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