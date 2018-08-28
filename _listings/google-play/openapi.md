swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications/{applicationId}:
    get:
      summary: Get Application
      description: Retrieves the metadata of the application with the given ID. If
        the requested application is not available for the specified platformType,
        the returned response will not include any instance data.
      operationId: games.applications.get
      x-api-path-slug: applicationsapplicationid-get
      parameters:
      - in: path
        name: applicationId
        description: The application ID from the Google Play developer console
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: language
        description: The preferred language to use for strings returned by this method
      - in: query
        name: platformType
        description: Restrict application details returned to the specific platform
      responses:
        200:
          description: OK
      tags:
      - Application