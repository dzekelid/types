---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Partners Property Types
  description: Gives the names and IDs of all available property types. This method
    differs from the property type lookup method in the client API component in that
    it can look up property types for any active Platinum MLS, not just those for
    which the client is a member.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partners/propertytypes:
    get:
      summary: Get Partners Property Types
      description: Gives the names and IDs of all available property types. This method
        differs from the property type lookup method in the client API component in
        that it can look up property types for any active Platinum MLS, not just those
        for which the client is a member.
      operationId: PartnersPropertytypesGet
      x-api-path-slug: partnerspropertytypes-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Property
      - Types
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