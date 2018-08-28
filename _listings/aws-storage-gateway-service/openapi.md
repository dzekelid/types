swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 1
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateVTLDeviceType:
    get:
      summary: Update VTL Device Type
      description: Updates the type of medium changer in a gateway-VTL.
      operationId: updateVTLDeviceType
      x-api-path-slug: actionupdatevtldevicetype-get
      parameters:
      - in: query
        name: DeviceType
        description: The type of medium changer you want to select
        type: string
      - in: query
        name: VTLDeviceARN
        description: The Amazon Resource Name (ARN) of the medium changer you want
          to select
        type: string
      responses:
        200:
          description: OK
      tags:
      - VTL Device Type