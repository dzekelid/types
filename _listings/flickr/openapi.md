---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.places.getPlaceTypes:
    get:
      summary: Places Get Place Types
      description: Fetches a list of available place types for Flickr.
      operationId: getRestMethodFlickr.places.getplacetypes
      x-api-path-slug: restmethodflickr-places-getplacetypes-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetPlaceTypes
---