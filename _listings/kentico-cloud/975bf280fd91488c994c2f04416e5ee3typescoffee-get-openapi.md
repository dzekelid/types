---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View a content type
  description: |-
    Retrieve a specific content type from your project by specifying its codename.

    See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /975bf280-fd91-488c-994c-2f04416e5ee3/types:
    get:
      summary: List content types
      description: |-
        Retrieve a list of content types in your project.

        See <https://developer.kenticocloud.com/v1/reference#list-content-types> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3types-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - List
      - Content
      - Types
  /975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee:
    get:
      summary: View a content type
      description: |-
        Retrieve a specific content type from your project by specifying its codename.

        See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesCoffeeGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3typescoffee-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Type
  /975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee/elements/processing:
    get:
      summary: View a content type element
      description: |-
        Retrieve a specific content type element by specifying its codename and its parent content type.

        See <https://developer.kenticocloud.com/v1/reference#view-a-content-type-element> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesCoffeeElementsProcessingGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3typescoffeeelementsprocessing-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Type
      - Element
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