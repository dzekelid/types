---
swagger: "2.0"
x-collection-name: Viddler
x-complete: 1
info:
  title: Viddler  API
  description: the-viddler-api-exposes-viddleru2019s-key-features-to-those-that-would-like-to-build-custom-solutions-on-top-of-viddleru2019s-video-platform-
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
---