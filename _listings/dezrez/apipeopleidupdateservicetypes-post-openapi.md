---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: "Dezrez Update the service types by PersonId\r\nThis cannot be used internally
    as they do not have the right to move status up to to approved \r\nOnly the client
    does"
  version: 1.0.0
  description: "Update the service types by personid\r\nthis cannot be used internally
    as they do not have the right to move status up to to approved \r\nonly the client
    does."
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/packrequiredtypes/{packid}:
    get:
      summary: Get a list of the packs required types (ie all of the types required
        by each document in each envelope)
      description: Get a list of the packs required types (ie all of the types required
        by each document in each envelope).
      operationId: DocumentGeneration_PackRequiredTypesBypackid
      x-api-path-slug: apidocumentgenerationpackrequiredtypespackid-get
      parameters:
      - in: path
        name: packid
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Packs
      - Required
      - Types
      - (ie
      - ""
      - Of
      - Types
      - Required
      - By
      - Each
      - Document
      - In
      - Each
      - Envelope)
  /api/documentgeneration/packsupportedsendmethods/{packid}:
    get:
      summary: Get a list of the supported sending methods for a correspondence (ie
        all of the types required by each document in each envelope)
      description: Get a list of the supported sending methods for a correspondence
        (ie all of the types required by each document in each envelope).
      operationId: DocumentGeneration_PackSupportedSendMethodsBypackid
      x-api-path-slug: apidocumentgenerationpacksupportedsendmethodspackid-get
      parameters:
      - in: path
        name: packid
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Supported
      - Sending
      - Methodsa
      - Correspondence
      - (ie
      - ""
      - Of
      - Types
      - Required
      - By
      - Each
      - Document
      - In
      - Each
      - Envelope)
  /api/people/{id}/updateservicetypes:
    post:
      summary: "Update the service types by PersonId\r\nThis cannot be used internally
        as they do not have the right to move status up to to approved \r\nOnly the
        client does"
      description: "Update the service types by personid\r\nthis cannot be used internally
        as they do not have the right to move status up to to approved \r\nonly the
        client does."
      operationId: People_UpdateServiceTypesByidByServiceTypes
      x-api-path-slug: apipeopleidupdateservicetypes-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: ServiceTypes
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Types
      - By
      - "PersonId\r\nThis"
      - Cannot
      - Be
      - Used
      - Internally
      - As
      - They
      - Do
      - Not
      - Have
      - Right
      - To
      - Move
      - Status
      - Up
      - To
      - To
      - Approved
      - Only
      - Client
      - Does
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