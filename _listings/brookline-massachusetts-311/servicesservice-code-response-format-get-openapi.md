---
swagger: "2.0"
x-collection-name: Brookline Massachusetts 311
x-complete: 0
info:
  title: Brookline Massachusetts 311 (extended) Definition Of A Service Type
  description: Define attributes associated with a service code. These attributes
    can be unique to the city/jurisdiction.
  termsOfService: (depends on server instance for example NYC http://dev.cityofchicago.org/docs/api/tos)
  contact:
    name: Open311 community
    url: http://wiki.open311.org/GeoReport_v2/
    email: discuss@lists.open311.org
  version: 1.0.0
host: spot.brooklinema.gov
basePath: /open311/v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services.{response_format}:
    get:
      summary: Service Types
      description: List acceptable service request types and their associated service
        codes. These request types can be unique to the city/jurisdiction.
      operationId: list-acceptable-service-request-types-and-their-associated-service-codes-these-request-types-can-be-
      x-api-path-slug: services-response-format-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - "311"
      - Service
      - Types
  /services/{service_code}.{response_format}:
    get:
      summary: (extended) Definition Of A Service Type
      description: Define attributes associated with a service code. These attributes
        can be unique to the city/jurisdiction.
      operationId: define-attributes-associated-with-a-service-code-these-attributes-can-be-unique-to-the-cityjurisdict
      x-api-path-slug: servicesservice-code-response-format-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: service_code
      responses:
        200:
          description: OK
      tags:
      - "311"
      - (extended)
      - Definition
      - Service
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