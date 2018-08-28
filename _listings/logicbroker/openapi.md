swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/ActivityEvents/EventTypes:
    get:
      summary: Gets a list of all possible event types.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: ActivityEvent_GetEventTypes
      x-api-path-slug: apiv1activityeventseventtypes-get
      responses:
        200:
          description: OK
      tags:
      - S
      - List
      - Of
      - ""
      - Possible
      - Event
      - Types