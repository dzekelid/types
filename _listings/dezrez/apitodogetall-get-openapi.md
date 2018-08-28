---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: "Dezrez Get the list of all ToDo's if no parameter is sent;\r\n<param name=\"filterToDo\">if
    provided will filter by ToDo type</param><param name=\"pageSize\"></param><param
    name=\"pageNumber\"></param>"
  version: 1.0.0
  description: "Get the list of all todo's if no parameter is sent;\r\n<param name=\"filtertodo\">if
    provided will filter by todo type</param><param name=\"pagesize\"></param><param
    name=\"pagenumber\"></param>."
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
  /api/role/{id}/documentfromplaceholder:
    get:
      summary: Get a single DocumentPlaceholder which is the 'slot' the particular
        document of type+source exists within.
      description: Get a single documentplaceholder which is the 'slot' the particular
        document of type+source exists within..
      operationId: Role_DocumentFromPlaceholderByidByplaceholderTypeByplaceholderSourceTypeBygroupId
      x-api-path-slug: apiroleiddocumentfromplaceholder-get
      parameters:
      - in: query
        name: groupId
        description: Optional group id to filter placeholder for a specific group
          relating to this role
      - in: path
        name: id
        description: Role id
      - in: query
        name: placeholderSourceType
        description: Where did the document come from to fit into the placeholder
          slot
      - in: query
        name: placeholderType
        description: Which type of document placeholder slot is this
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Single
      - DocumentPlaceholder
      - Which
      - Is
      - Slot
      - Particular
      - Document
      - Of
      - Type+source
      - Exists
      - Within
  /api/todo/getall:
    get:
      summary: "Get the list of all ToDo's if no parameter is sent;\r\n<param name=\"filterToDo\">if
        provided will filter by ToDo type</param><param name=\"pageSize\"></param><param
        name=\"pageNumber\"></param>"
      description: "Get the list of all todo's if no parameter is sent;\r\n<param
        name=\"filtertodo\">if provided will filter by todo type</param><param name=\"pagesize\"></param><param
        name=\"pagenumber\"></param>."
      operationId: DefaultToDo_GetAllBypageSizeBypageNumberByfilterToDo.filterCategoryByfilterToDo.toDoTypeByfilterToDo
      x-api-path-slug: apitodogetall-get
      parameters:
      - in: query
        name: filterToDo.branchId
      - in: query
        name: filterToDo.filterCategory
      - in: query
        name: filterToDo.negotiatorIds
      - in: query
        name: filterToDo.toDoType
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - ToDos
      - If
      - "No"
      - Parameter
      - Is
      - "Sent;\r\n<param"
      - Name=filterToDo>if
      - Provided
      - Will
      - Filter
      - By
      - ToDo
      - Type<
      - Param><param
      - Name=pageSize><
      - Param><param
      - Name=pageNumber><
      - Param>
  /api/documentgeneration/documentSubTypes:
    get:
      summary: Get the appropriate document sub types for a document type
      description: Get the appropriate document sub types for a document type.
      operationId: DocumentGeneration_getDocumentSubTypesByDocumentTypeSystemName
      x-api-path-slug: apidocumentgenerationdocumentsubtypes-get
      parameters:
      - in: query
        name: DocumentTypeSystemName
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Appropriate
      - Document
      - Sub
      - Typesa
      - Document
      - Type
  /api/account/pm/list:
    post:
      summary: Get list of accounts with sorting and searching and by type of group
        for the accounts
      description: Get list of accounts with sorting and searching and by type of
        group for the accounts.
      operationId: Account_GetPMAccountsBydataContractBypageSizeBypageNumber
      x-api-path-slug: apiaccountpmlist-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Accounts
      - Sorting
      - Searching
      - By
      - Type
      - Of
      - Groupthe
      - Accounts
  /api/role/auction/{id}/settype:
    post:
      summary: Set the type of auction role (Commercial or Residential)
      description: Set the type of auction role (commercial or residential).
      operationId: AuctionRole_SetTypeByidByauctionRoleTypeSystemName
      x-api-path-slug: apiroleauctionidsettype-post
      parameters:
      - in: query
        name: auctionRoleTypeSystemName
        description: The auction role type
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Type
      - Of
      - Auction
      - Role
      - (Commercial
      - Residential)
  /api/customfieldgroup/{typeName}:
    get:
      summary: Get a list of custom field groups for a type and optional group name
        specified.
      description: Get a list of custom field groups for a type and optional group
        name specified..
      operationId: CustomFieldGroup_GetBytypeNameBygroupName
      x-api-path-slug: apicustomfieldgrouptypename-get
      parameters:
      - in: query
        name: groupName
        description: An optional parameter to filter by group name
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: typeName
        description: The name of the type to get the custom field groups for
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Custom
      - Field
      - Groupsa
      - Type
      - Optional
      - Group
      - Name
      - Specified
  /api/documentgeneration/previewpack:
    post:
      summary: Generates a pack using the first selected group/property of a type
        to get a quick preview of the pack
      description: Generates a pack using the first selected group/property of a type
        to get a quick preview of the pack.
      operationId: DocumentGeneration_PreviewPackByrandomPackDataContract
      x-api-path-slug: apidocumentgenerationpreviewpack-post
      parameters:
      - in: body
        name: randomPackDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Pack
      - Using
      - First
      - Selected
      - Group
      - Property
      - Of
      - Type
      - To
      - Get
      - Quick
      - Preview
      - Of
      - Pack
  /api/documentgeneration/bulkpropertyownercommunication:
    post:
      summary: "Generates a bulk communication pack out to multiple vendors of properties.\r\nThis
        will ignore the target type set, as the document could only ever find the
        vendor as the contact item, so it always defaults\r\nto a target type of vendor/owner"
      description: "Generates a bulk communication pack out to multiple vendors of
        properties.\r\nthis will ignore the target type set, as the document could
        only ever find the vendor as the contact item, so it always defaults\r\nto
        a target type of vendor/owner."
      operationId: DocumentGeneration_BulkPropertyVendorCommunicationBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationbulkpropertyownercommunication-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Bulk
      - Communication
      - Pack
      - Out
      - To
      - Multiple
      - Vendors
      - Of
      - Properties
      - This
      - Will
      - Ignore
      - Target
      - Type
      - Set
      - ""
      - As
      - Document
      - Could
      - Only
      - Ever
      - Find
      - Vendor
      - As
      - Contact
      - Item
      - ""
      - So
      - It
      - Always
      - "Defaults\r\nTo"
      - Target
      - Type
      - Of
      - Vendor
      - Owner
  /api/documentgeneration/templates/{templateType}:
    get:
      summary: Returns a list of mergable templates for any type associated to this
        agency
      description: Returns a list of mergable templates for any type associated to
        this agency.
      operationId: DocumentGeneration_GetTemplatesBytemplateType
      x-api-path-slug: apidocumentgenerationtemplatestemplatetype-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: templateType
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Mergable
      - Templatesany
      - Type
      - Associated
      - To
      - This
      - Agency
  /api/documentgeneration/targetgroups:
    get:
      summary: Get an enum by its type and system name
      description: Get an enum by its type and system name.
      operationId: DocumentGeneration_TargetGroups
      x-api-path-slug: apidocumentgenerationtargetgroups-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Enum
      - By
      - Its
      - Type
      - System
      - Name
  /api/enum/marketingrolestatus:
    get:
      summary: Get an enum by its type and system name
      description: Get an enum by its type and system name.
      operationId: Enum_GetMarketingRoleStatusBytransactionType
      x-api-path-slug: apienummarketingrolestatus-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: transactionType
        description: The typeo of marketingrole to get
      responses:
        200:
          description: OK
      tags:
      - Enum
      - By
      - Its
      - Type
      - System
      - Name
  /api/stats/visited/{entityType}:
    get:
      summary: Get all recent history of 'pages' visited on Rezi for a given entity
        type.
      description: Get all recent history of 'pages' visited on rezi for a given entity
        type..
      operationId: Stats_VisitedByentityType
      x-api-path-slug: apistatsvisitedentitytype-get
      parameters:
      - in: path
        name: entityType
        description: Either Groups, Properties or will default to all if nothing passed
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Recent
      - History
      - Of
      - Pages
      - Visited
      - "On"
      - Rezia
      - Given
      - Entity
      - Type
  /api/tenancy/{id}/settenancytype:
    post:
      summary: Updated tenancy type
      description: Updated tenancy type.
      operationId: Tenancy_SetTenancyTypeByidBytenancyTypeName
      x-api-path-slug: apitenancyidsettenancytype-post
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenancyTypeName
        description: Tenancy Type name
      responses:
        200:
          description: OK
      tags:
      - D
      - Tenancy
      - Type
  /api/accountingsystem/enum/{enumType}:
    get:
      summary: ""
      description: .
      operationId: AccountingSystem_GetAccountingEnumsByenumType
      x-api-path-slug: apiaccountingsystemenumenumtype-get
      parameters:
      - in: path
        name: enumType
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/negotiator/my/properties/{roleType}:
    get:
      summary: Used for the Property Sales Dashboard to return a list of the negotiator's
        properties.
      description: Used for the property sales dashboard to return a list of the negotiator's
        properties..
      operationId: Negotiator_PropertiesByroleTypeBypageSizeBypageNumber
      x-api-path-slug: apinegotiatormypropertiesroletype-get
      parameters:
      - in: query
        name: pageNumber
        description: which page number of results to choose
      - in: query
        name: pageSize
        description: how many properties to return (default 10)
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleType
        description: the PropertyMarketingRole type
      responses:
        200:
          description: OK
      tags:
      - Usedthe
      - Property
      - Sales
      - Dashboard
      - To
      - Return
      - List
      - Of
      - Negotiators
      - Properties
  /api/stats/RecordVisit/{pageType}/{entityId}:
    post:
      summary: Record and timestamp a visit to a 'page' on Rezi.
      description: Record and timestamp a visit to a 'page' on rezi..
      operationId: Stats_RecordVisitBypageTypeByentityIdByroleId
      x-api-path-slug: apistatsrecordvisitpagetypeentityid-post
      parameters:
      - in: path
        name: entityId
        description: The relative entitiyId e
      - in: path
        name: pageType
        description: GroupHub, PropertyHub, MarketingHub, PersonHub, SalesProgressionHub
          or PreTenancyHub
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleId
        description: The RoleId if applicable (can be null if omitted)
      responses:
        200:
          description: OK
      tags:
      - Record
      - Timestamp
      - Visit
      - To
      - Page
      - "On"
      - Rezi
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