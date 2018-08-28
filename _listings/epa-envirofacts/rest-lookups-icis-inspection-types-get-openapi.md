---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services ECHO ICIS NPDES Inspection Types Lookup Service
  description: Returns the ICIS NPDES Compliance Monitoring Type Code and Description.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest_lookups.icis_inspection_types:
    get:
      summary: ECHO ICIS NPDES Inspection Types Lookup Service
      description: Returns the ICIS NPDES Compliance Monitoring Type Code and Description.
      operationId: returns-the-icis-npdes-compliance-monitoring-type-code-and-description-
      x-api-path-slug: rest-lookups-icis-inspection-types-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - ICIS
      - NPDES
      - Inspection
      - Types
      - Lookup
      - Service
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