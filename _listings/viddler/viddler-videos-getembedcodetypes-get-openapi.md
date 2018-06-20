---
swagger: "2.0"
x-collection-name: Viddler
x-complete: 0
info:
  title: Viddler  API Videos GetEmbedCodeTypes
  description: Return a list of the embed code types for your account.
  termsOfService: http://www.viddler.com/terms-of-use/
  version: v2
host: api.viddler.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  viddler.videos.getEmbedCodeTypes:
    get:
      summary: Videos GetEmbedCodeTypes
      description: Return a list of the embed code types for your account.
      operationId: videos-getembedcodetypes
      x-api-path-slug: viddler-videos-getembedcodetypes-get
      parameters:
      - in: query
        name: sessionid
      responses:
        200:
          description: OK
      tags:
      - Viddler
      - Videos
      - GetEmbedCodeTypes
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