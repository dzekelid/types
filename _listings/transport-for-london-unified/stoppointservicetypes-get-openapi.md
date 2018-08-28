---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Stop Point  Service Types
  description: Gets the service types for a given stoppoint.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Line/Meta/ServiceTypes:
    get:
      summary: Line  Meta  Service Types
      description: Gets a list of valid servicetypes to filter on.
      operationId: Line_MetaServiceTypes
      x-api-path-slug: linemetaservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Service
      - Types
  /Mode/ActiveServiceTypes:
    get:
      summary: Mode  Active Service Types
      description: "Returns the service type active for a mode.\r\n            currently
        only supports tube."
      operationId: Mode_GetActiveServiceTypes
      x-api-path-slug: modeactiveservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Mode
      - ""
      - Active
      - Service
      - Types
  /Place/Meta/PlaceTypes:
    get:
      summary: Place  Meta  Place Types
      description: Gets a list of the available types of place..
      operationId: Place_MetaPlaceTypes
      x-api-path-slug: placemetaplacetypes-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Place
      - Types
  /Place/Type/{types}:
    get:
      summary: Place  Type types
      description: Gets all places of a given type.
      operationId: Place_GetByType
      x-api-path-slug: placetypetypes-get
      parameters:
      - in: query
        name: activeOnly
        description: An optional parameter to limit the results to active records
          only (Currently only the VariableMessageSign place type is supported)
      - in: path
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Type
      - Types
  /StopPoint/Meta/StopTypes:
    get:
      summary: Stop Point  Meta  Stop Types
      description: Gets the list of available stoppoint types.
      operationId: StopPoint_MetaStopTypes
      x-api-path-slug: stoppointmetastoptypes-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Stop
      - Types
  /StopPoint/ServiceTypes:
    get:
      summary: Stop Point  Service Types
      description: Gets the service types for a given stoppoint.
      operationId: StopPoint_GetServiceTypes
      x-api-path-slug: stoppointservicetypes-get
      parameters:
      - in: query
        name: id
        description: The Naptan id of the stop
      - in: query
        name: lineIds
        description: The lines which contain the given Naptan id (all lines relevant
          to the given stoppoint if empty)
      - in: query
        name: modes
        description: The modes which the lines are relevant to (all if empty)
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Service
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