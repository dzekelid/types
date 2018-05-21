---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 1
info:
  title: YouTube
  description: youtube-allows-users-to-upload-view-rate-share-add-to-favorites-report-comment-on-videos-and-subscribe-to-other-users-it-offers-a-wide-variety-of-usergenerated-and-corporate-media-videos-available-content-includes-video-clips-tv-show-clips-music-videos-short-and-documentary-films-audio-recordings-movie-trailers-live-streams-and-other-content-such-as-video-blogging-short-original-videos-and-educational-videos-most-of-the-content-on-youtube-is-uploaded-by-individuals-but-media-corporations-including-cbs-the-bbc-vevo-and-hulu-offer-some-of-their-material-via-youtube-as-part-of-the-youtube-partnership-program-unregistered-users-can-only-watch-videos-on-the-site-while-registered-users-are-permitted-to-upload-an-unlimited-number-of-videos-and-add-comments-to-videos
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/reportTypes:
    get:
      summary: Get Reporttypes
      description: Lists report types.
      operationId: getV1Reporttypes
      x-api-path-slug: v1reporttypes-get
      parameters:
      - in: query
        name: includeSystemManaged
        description: If set to true, also system-managed report types will be returned;otherwise
          only the report types that can be used to create new reportingjobs will
          be returned
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results the server should return
      responses:
        200:
          description: OK
      tags:
      - V1
      - Reporttypes
    parameters:
      summary: Parameters Reporttypes
      description: Parameters v1 reporttypes
      operationId: parametersV1Reporttypes
      x-api-path-slug: v1reporttypes-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Reporttypes
---