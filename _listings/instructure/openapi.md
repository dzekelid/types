swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/self/communication_channels/{type}/address/notification_preferences:
    put:
      summary: Update multiple preferences
      description: Update multiple preferences.
      operationId: update-multiple-preferences
      x-api-path-slug: usersselfcommunication-channelstypeaddressnotification-preferences-put
      parameters:
      - in: query
        name: notification_preferences[X][frequency]
        description: The desired frequency for &lt;X&gt; notification
      responses:
        200:
          description: OK
      tags:
      - Users
      - Self
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
  /users/self/communication_channels/{type}/address/notification_preferences/{notification}:
    put:
      summary: Update a preference
      description: Update a preference.
      operationId: update-a-preference
      x-api-path-slug: usersselfcommunication-channelstypeaddressnotification-preferencesnotification-put
      parameters:
      - in: query
        name: notification_preferences[frequency]
        description: The desired frequency for this notification
      responses:
        200:
          description: OK
      tags:
      - Users
      - Self
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
      - Notification
  /users/{user_id}/communication_channels/type/{address}:
    delete:
      summary: Delete a communication channel
      description: Delete a communication channel.
      operationId: delete-a-communication-channel
      x-api-path-slug: usersuser-idcommunication-channelstypeaddress-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
      - Address
  /users/{user_id}/communication_channels/type/{address}/notification_preferences:
    get:
      summary: List preferences
      description: List preferences.
      operationId: list-preferences
      x-api-path-slug: usersuser-idcommunication-channelstypeaddressnotification-preferences-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
  /users/{user_id}/communication_channels/type/{address}/notification_preferences/notification:
    get:
      summary: Get a preference
      description: Get a preference.
      operationId: get-a-preference
      x-api-path-slug: usersuser-idcommunication-channelstypeaddressnotification-preferencesnotification-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
      - Notification