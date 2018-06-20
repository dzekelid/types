---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: hetras Hotel API Version 0
  version: v0
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/room_types:
    get:
      summary: Get a list with the details of all room types for for the specified
        hotel id.
      description: With this call you can load the details about a all available room
        types for the specified hotel.
      operationId: RoomTypes_GetRoomTypes
      x-api-path-slug: apihotelv0hotelshotelidroom-types-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
        description: The hotel id the room type belongs to
      responses:
        200:
          description: OK
      tags:
      - List
      - Details
      - Of
      - ""
      - Room
      - Typesfor
      - Specified
      - Hotel
      - Id
---