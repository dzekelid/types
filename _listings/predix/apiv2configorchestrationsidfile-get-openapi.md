---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Runtime Download an orchestration artifact file by orchestration
    id and artifact type.
  version: 1.0.0
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/config/orchestrations/{id}/file:
    get:
      summary: Download an orchestration artifact file by orchestration id and artifact
        type.
      description: The file is downloaded as an octet-stream. If the type is bpmn,
        then then bpmn xml is downloaded. If the type is portToFieldMap, then the
        system expects analyticStepId to download the portToFieldMap for the given
        step
      operationId: downloadArtifactByType
      x-api-path-slug: apiv2configorchestrationsidfile-get
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: path
        name: id
        description: orchestration configuration entry id
      - in: query
        name: name
        description: artifact name (analytic step id)
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: query
        name: type
        description: artifact type (Ex
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Download
      - Orchestration
      - Artifact
      - File
      - By
      - Orchestration
      - Id
      - Artifact
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