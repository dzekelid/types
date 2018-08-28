---
swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 0
info:
  title: HPE OneSphere API Get Zone Types
  description: Returns all zone types.
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog-types:
    get:
      summary: Get Catalog Types
      description: Returns catalog types.
      operationId: FindCatalogTypes
      x-api-path-slug: catalogtypes-get
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Types
  /provider-types:
    get:
      summary: Get Prover Types
      description: Returns provider types.
      operationId: FindProviderTypes
      x-api-path-slug: providertypes-get
      responses:
        200:
          description: OK
      tags:
      - Prover
      - Types
  /service-types:
    get:
      summary: Get Service Types
      description: Returns all service types. It requires the **consumer** global
        role.
      operationId: FindServiceTypes
      x-api-path-slug: servicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Service
      - Types
  /service-types/{id}:
    get:
      summary: Get Service Types
      description: Return a service type based on its id. It requires the **consumer**
        global role.
      operationId: GetServiceTypeById
      x-api-path-slug: servicetypesid-get
      parameters:
      - in: path
        name: id
        description: ID of service type to fetch
      responses:
        200:
          description: OK
      tags:
      - Service
      - Types
  /zone-types:
    get:
      summary: Get Zone Types
      description: Returns all zone types.
      operationId: FindZoneTypes
      x-api-path-slug: zonetypes-get
      responses:
        200:
          description: OK
      tags:
      - Zone
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