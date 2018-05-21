---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson IoT Platform Get the draft physical interface associated with
    the device type
  description: |-
    Retrieve the draft physical interface that has been associated with the
    device type.  At least one active physical interface must be associated
    with the device type before any mappings can be defined that will
    generate state for the device.
  version: 1.0.0
basePath: /api/v0002
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /event/types:
    get:
      summary: Query active event types
      description: |-
        Event types are used to model the events that are published to the
        Watson IoT Platform.  An event type must be created in an organization
        before more complex processing can be performed on the native event.

        The **/event/types** endpoint returns the list of all of the active
        event types that have been defined for the organization in the Watson
        IoT Platform.  Various query parameters can be used to filter, sort and
        page through the list of active event types that are returned.
      operationId: event-types-are-used-to-model-the-events-that-are-published-to-thewatson-iot-platform--an-event-type
      x-api-path-slug: eventtypes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Event
      - Types
  /event/types/{eventTypeId}:
    get:
      summary: Get an active event type
      description: Retrieve the active event type with the specified id.
      operationId: retrieve-the-active-event-type-with-the-specified-id
      x-api-path-slug: eventtypeseventtypeid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Event
      - Types
      - EventTypeId
  /draft/event/types:
    get:
      summary: Query draft event types
      description: |-
        Event types are used to model the events that are published to the
        Watson IoT Platform.  An event type must be created in an organization
        before more complex processing can be performed on the native event.

        The **/draft/event/types** endpoint returns the list of all of the draft
        event types that have been defined for the organization in the Watson
        IoT Platform.  Various query parameters can be used to filter, sort and
        page through the list of draft event types that are returned.
      operationId: event-types-are-used-to-model-the-events-that-are-published-to-thewatson-iot-platform--an-event-type
      x-api-path-slug: drafteventtypes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Event
      - Types
    post:
      summary: Create a draft event type
      description: |-
        Creates a new draft event type for the organization in the Watson IoT
        Platform.  The draft event type must reference the schema definition
        that defines the structure of the inbound MQTT event.
      operationId: creates-a-new-draft-event-type-for-the-organization-in-the-watson-iotplatform--the-draft-event-type-
      x-api-path-slug: drafteventtypes-post
      parameters:
      - in: body
        name: Event Type
        description: The JSON representation of the draft event type
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Event
      - Types
  /draft/event/types/{eventTypeId}:
    get:
      summary: Get a draft event type
      description: Retrieve the draft event type with the specified id.
      operationId: retrieve-the-draft-event-type-with-the-specified-id
      x-api-path-slug: drafteventtypeseventtypeid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Event
      - Types
      - EventTypeId
    put:
      summary: Update a draft event type
      description: "Updates the draft event type with the specified id. The following\nproperties
        can be updated:\n\n  - name\n  - description\n  - schemaId\n\nNote that if
        the description field is omitted from the body of the\nupdate, then any existing
        description will be removed from the event\ntype.\n  \nAny changes made to
        the values of the following properties will be\nignored:\n\n  - created\n
        \ - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values of these
        properties are set on the server as a result of a\nsuccessful update."
      operationId: updates-the-draft-event-type-with-the-specified-id-the-followingproperties-can-be-updated---name---d
      x-api-path-slug: drafteventtypeseventtypeid-put
      parameters:
      - in: body
        name: Event Type
        description: The JSON representation of the event type
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Event
      - Types
      - EventTypeId
    delete:
      summary: Delete a draft event type
      description: "Deletes the draft event type with the specified id from the organization\nin
        the Watson IoT Platform.\n\nPlease note the the delete will fail if the draft
        event type is being \nreferenced by a physical interface."
      operationId: deletes-the-draft-event-type-with-the-specified-id-from-the-organizationin-the-watson-iot-platformpl
      x-api-path-slug: drafteventtypeseventtypeid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Event
      - Types
      - EventTypeId
  /device/types:
    get:
      summary: List device types
      description: |-
        Sorting can be performed on any of the following properties (sort
        order can be reversed by prefixing the property name with '-'):
        - id
        - description
        - deviceInfo.description
        - deviceInfo.descriptiveLocation
        - deviceInfo.serialNumber
        - deviceInfo.deviceClass
        - deviceInfo.fwVersion
        - deviceInfo.hwVersion
        - deviceInfo.manufacturer
        - deviceInfo.model

        The following facets are supported:
        - deviceInfo.deviceClass
        - deviceInfo.fwVersion
        - deviceInfo.hwVersion
        - deviceInfo.manufacturer
        - deviceInfo.model
      operationId: sorting-can-be-performed-on-any-of-the-following-properties-sortorder-can-be-reversed-by-prefixing-t
      x-api-path-slug: devicetypes-get
      parameters:
      - in: query
        name: description
        description: Optional filter of results by description
      - in: query
        name: id
        description: Optional filter of results by ID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
  /device/types/{typeId}:
    patch:
      summary: Perform an operation against a device type
      description: |-
        Performs the specified operation against the device type. The following
        values can be specified for the operation property:

          - deactivate-configuration

        The **deactivate-configuration** operation will remove any activate
        configuration that is currently associated with the device type. If any
        instances of the device type exist, the state for those devices will be
        deleted as a result of performing the **deactivate-configuration**
        operation. The **deactivate-configuration** operation will fail if
        any instances of the device type are being aggregated into an instance
        of a thing.
      operationId: performs-the-specified-operation-against-the-device-type-the-followingvalues-can-be-specified-for-th
      x-api-path-slug: devicetypestypeid-patch
      parameters:
      - in: body
        name: Device Type Operation
        description: The JSON representation of a device type operation
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
  /device/types/{typeId}/physicalinterface:
    get:
      summary: Get the active physical interface associated with the device type
      description: |-
        Retrieve the active physical interface that has been associated with the
        device type.  At least one active physical interface must be associated
        with the device type before any mappings can be defined that will
        generate state for the device.
      operationId: retrieve-the-active-physical-interface-that-has-been-associated-with-thedevice-type--at-least-one-ac
      x-api-path-slug: devicetypestypeidphysicalinterface-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Physicalinterface
  /device/types/{typeId}/logicalinterfaces:
    get:
      summary: |-
        Get the list of active logical interfaces associated with the device
        type
      description: |-
        Retrieve the list of active logical interfaces that have been
        associated with the device type.  At least one logical interface
        must be associated with the device type before any mappings can be
        defined that will generate state for the device.
      operationId: retrieve-the-list-of-active-logical-interfaces-that-have-beenassociated-with-the-device-type--at-lea
      x-api-path-slug: devicetypestypeidlogicalinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Logical interfaces
  /device/types/{typeId}/mappings:
    get:
      summary: Get the list of active property mappings for the device type
      description: |-
        Retrieve the list of active property mappings for the specified device
        type.  A property mapping defines how properties from inbound events are
        mapped to properties defined on an logical interface associated with
        the device type.
      operationId: retrieve-the-list-of-active-property-mappings-for-the-specified-devicetype--a-property-mapping-defin
      x-api-path-slug: devicetypestypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Mappings
  /device/types/{typeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the active property mappings for a specific logical interface
        for a device type.
      description: |-
        Retrieves the active property mappings for a specific logical
        interface for the device type.
      operationId: retrieves-the-active-property-mappings-for-a-specific-logicalinterface-for-the-device-type
      x-api-path-slug: devicetypestypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Mappings
      - LogicalInterfaceId
  /draft/device/types:
    get:
      summary: List device types associated with an logical or physical interface
      description: |-
        Retrieves the list of device types that are associated with the
        logical interface and/or physical interface with the ids specified
        using the corresponding query parameters.

        Note that at least one of the following query parameters must be
        specified:

          - logicalInterfaceId
          - physicalInterfaceId
      operationId: retrieves-the-list-of-device-types-that-are-associated-with-thelogical-interface-andor-physical-inte
      x-api-path-slug: draftdevicetypes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
  /draft/device/types/{typeId}:
    patch:
      summary: Perform an operation against a draft device type
      description: "Performs the specified operation against the draft device type.
        The\nfollowing values can be specified for the operation property:\n\n  -
        validate-configuration\n  - activate-configuration\n  - list-differences\n\nThe
        **validate-configuration** operation will analyze all of the \nconfiguration
        associated with the draft device type to determine if it\nis valid.  If the
        configuration is invalid, a list of the issues will\nbe returned in the body
        of the response.  \n \nThe **activate-configuration** operation will make
        the configuration\nassociated with the draft device type active. The\n**activate-configuration**
        operation must have been performed against a\ndraft device type before any
        state is generated for instances of that\ntype.\n\nThe **list-differences**
        operation will return a list of the differences\nthat exist between the active
        configuration for the device type, if\nany, and the draft configuration."
      operationId: performs-the-specified-operation-against-the-draft-device-type-thefollowing-values-can-be-specified-
      x-api-path-slug: draftdevicetypestypeid-patch
      parameters:
      - in: body
        name: Device Type Operation
        description: The JSON representation of a device type operation
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
  /draft/device/types/{typeId}/physicalinterface:
    get:
      summary: Get the draft physical interface associated with the device type
      description: |-
        Retrieve the draft physical interface that has been associated with the
        device type.  At least one active physical interface must be associated
        with the device type before any mappings can be defined that will
        generate state for the device.
      operationId: retrieve-the-draft-physical-interface-that-has-been-associated-with-thedevice-type--at-least-one-act
      x-api-path-slug: draftdevicetypestypeidphysicalinterface-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Physicalinterface
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