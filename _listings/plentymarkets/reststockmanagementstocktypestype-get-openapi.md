---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List stock by warehouse type
  description: Lists stock for all warehouses of the same warehouse type. The name
    of the type must be specified. Currently the only type available is 'sales'.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/addresses/option_types:
    get:
      summary: List address option types
      description: List address option types.
      operationId: getRestAccountsAddressesOptionTypes
      x-api-path-slug: restaccountsaddressesoption-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Option
      - Types
    post:
      summary: Create an address option type
      description: Create an address option type.
      operationId: postRestAccountsAddressesOptionTypes
      x-api-path-slug: restaccountsaddressesoption-types-post
      parameters:
      - in: body
        name: /rest/accounts/addresses/option_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
  /rest/accounts/addresses/relation_types:
    get:
      summary: List address relation types
      description: List address relation types.
      operationId: getRestAccountsAddressesRelationTypes
      x-api-path-slug: restaccountsaddressesrelation-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Relation
      - Types
  /rest/accounts/addresses/relations/types/applications/{application}/{lang}:
    get:
      summary: List address relation types
      description: |-
        Lists address relation types. The application and the language must be specified.
        <br>Possible applications:
        <ul>
        <li>contact</li>
        <li>order</li>
        <li>warehouse</li>
        <li>pos</li>
        </ul>
      operationId: getRestAccountsAddressesRelationsTypesApplicationsApplicationLang
      x-api-path-slug: restaccountsaddressesrelationstypesapplicationsapplicationlang-get
      parameters:
      - in: path
        name: application
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Relation
      - Types
  /rest/accounts/contacts/option_types:
    get:
      summary: List contact option types
      description: List contact option types.
      operationId: getRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-get
      parameters:
      - in: query
        name: with
        description: Lists possible option sub-types for each listed option if the
          parameter subTypes is set
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Option
      - Types
    post:
      summary: Create a contact option type
      description: Create a contact option type.
      operationId: postRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/types:
    get:
      summary: List contact types
      description: List contact types.
      operationId: getRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Types
    post:
      summary: Create a contact type
      description: Create a contact type.
      operationId: postRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/listings/stock_dependence_types:
    get:
      summary: List listing stock dependence types
      description: Lists listing stock dependence types.
      operationId: getRestListingsStockDependenceTypes
      x-api-path-slug: restlistingsstock-dependence-types-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: with
        description: An array with child instances to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Listing
      - Stock
      - Dependence
      - Types
  /rest/listings/types:
    get:
      summary: List listing types
      description: Lists all listing types.
      operationId: getRestListingsTypes
      x-api-path-slug: restlistingstypes-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Listing
      - Types
  /rest/logs/reference_types:
    get:
      summary: Get all registered reference types.
      description: Get all registered reference types..
      operationId: getRestLogsReferenceTypes
      x-api-path-slug: restlogsreference-types-get
      responses:
        200:
          description: OK
      tags:
      - Registered
      - Reference
      - Types
  /rest/orders/dates/types:
    get:
      summary: List order date types
      description: List order date types.
      operationId: getRestOrdersDatesTypes
      x-api-path-slug: restordersdatestypes-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Order
      - Date
      - Types
  /rest/orders/properties/types:
    get:
      summary: List order property types
      description: Lists property types and their names in all languages. Optionally
        one or more languages can be specified to get a limited response.
      operationId: getRestOrdersPropertiesTypes
      x-api-path-slug: restorderspropertiestypes-get
      parameters:
      - in: query
        name: lang
        description: Languages to be loaded with the type model
      responses:
        200:
          description: OK
      tags:
      - List
      - Order
      - Property
      - Types
    post:
      summary: Create an order property type
      description: Create an order property type.
      operationId: postRestOrdersPropertiesTypes
      x-api-path-slug: restorderspropertiestypes-post
      parameters:
      - in: body
        name: /rest/orders/properties/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Order
      - Property
      - Type
  /rest/orders/shipping/package_types:
    get:
      summary: List shipping package types
      description: List shipping package types.
      operationId: getRestOrdersShippingPackageTypes
      x-api-path-slug: restordersshippingpackage-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Shipping
      - Package
      - Types
  /rest/payment/properties/types/names/{lang?}:
    get:
      summary: List names of property types
      description: List names of property types.
      operationId: getRestPaymentPropertiesTypesNamesLang
      x-api-path-slug: restpaymentpropertiestypesnameslang-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: path
        name: lang?
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Names
      - Of
      - Property
      - Types
  /rest/payments/properties/types:
    get:
      summary: List property types
      description: Lists all property types. The language must be specified.
      operationId: getRestPaymentsPropertiesTypes
      x-api-path-slug: restpaymentspropertiestypes-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Types
    post:
      summary: Create a property type
      description: Create a property type.
      operationId: postRestPaymentsPropertiesTypes
      x-api-path-slug: restpaymentspropertiestypes-post
      parameters:
      - in: body
        name: /rest/payments/properties/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
    put:
      summary: Update a property type
      description: Update a property type.
      operationId: putRestPaymentsPropertiesTypes
      x-api-path-slug: restpaymentspropertiestypes-put
      parameters:
      - in: body
        name: /rest/payments/properties/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
  /rest/properties/groups/surcharge/types:
    get:
      summary: Get surcharge types from module configuration
      description: Get surcharge types from module configuration.
      operationId: getRestPropertiesGroupsSurchargeTypes
      x-api-path-slug: restpropertiesgroupssurchargetypes-get
      responses:
        200:
          description: OK
      tags:
      - Surcharge
      - Types
      - From
      - Module
      - Configuration
  /rest/properties/groups/types:
    get:
      summary: Get group types from module configuration
      description: Get group types from module configuration.
      operationId: getRestPropertiesGroupsTypes
      x-api-path-slug: restpropertiesgroupstypes-get
      responses:
        200:
          description: OK
      tags:
      - Group
      - Types
      - From
      - Module
      - Configuration
  /rest/accounting/locations/{locationId}/{type}/posting_accounts:
    get:
      summary: Get all posting accounts by locationId and type
      description: Get all posting accounts by locationid and type.
      operationId: getRestAccountingLocationsLocationTypeAddingAccounts
      x-api-path-slug: restaccountinglocationslocationidtypeposting-accounts-get
      parameters:
      - in: path
        name: locationId
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
      - By
      - LocationId
      - Type
  /rest/accounts/addresses/option_types/{optionTypeId}:
    delete:
      summary: Delete an address option type
      description: Deletes an address option type. The ID of the option type must
        be specified.
      operationId: deleteRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-delete
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
    get:
      summary: Get an address option type
      description: Gets an address option type. The ID of the option type must be
        specified.
      operationId: getRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-get
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
    put:
      summary: Update an address option type
      description: Updates an address option type. The ID of the option type must
        be specified.
      operationId: putRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-put
      parameters:
      - in: body
        name: /rest/accounts/addresses/option_types/{optionTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
  /rest/accounts/contacts/option_types/{optionTypeId}:
    delete:
      summary: Delete a contact option type
      description: Deletes a contact option type. The ID of the option type must be
        specified.
      operationId: deleteRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-delete
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    get:
      summary: Get a contact option type
      description: Gets a contact option type. The ID of the option type must be specified.
      operationId: getRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-get
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    put:
      summary: Update a contact option type
      description: Updates a contact option type. The ID of the option type must be
        specified.
      operationId: putRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types/{optionTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/types/{typeId}:
    delete:
      summary: Delete a contact type
      description: Deletes a contact type. The ID of the contact type must be specified.
      operationId: deleteRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-delete
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    get:
      summary: Get a contact type
      description: Gets a contact type. The ID of the contact type must be specified.
      operationId: getRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    put:
      summary: Update a contact type
      description: Updates a contact type. The ID of the contact type must be specified.
      operationId: putRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/types/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}/addresses:
    post:
      summary: Create an address for existing contact and type
      description: Creates an address. The ID of the contact must be specified.
      operationId: postRestAccountsContactsContactAddresses
      x-api-path-slug: restaccountscontactscontactidaddresses-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}/addresses
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      - in: query
        name: isPrimary
        description: Sets a contact address per address type as the primary address
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Addressexisting
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}/addresses/{addressId}/types/{addressTypeId}/primary:
    put:
      summary: Set a contact address per address type as the primary address
      description: Sets a contact address per address type as the primary address.
        The ID of the contact, the ID of the address and the ID of the address type
        must be specified. A primary address is also definable if you create or update
        a contact address.
      operationId: putRestAccountsContactsContactAddressesAddressTypesAddresstypePrimary
      x-api-path-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidprimary-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: addressTypeId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Contact
      - Address
      - Per
      - Address
      - Type
      - As
      - Primary
      - Address
  /rest/items/barcodes/type/{type}:
    get:
      summary: List barcodes by type
      description: Lists all barcodes of a specific type. The type must be specified.
      operationId: getRestItemsBarcodesTypeType
      x-api-path-slug: restitemsbarcodestypetype-get
      parameters:
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - List
      - Barcodes
      - By
      - Type
  /rest/listings/stock_dependence_types/{id}:
    get:
      summary: Get a listing stock dependence type
      description: Gets a listing stock dependence type by given ID.
      operationId: getRestListingsStockDependenceTypes
      x-api-path-slug: restlistingsstock-dependence-typesid-get
      parameters:
      - in: path
        name: id
      - in: query
        name: with
        description: An array with child instances to be loaded
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Stock
      - Dependence
      - Type
  /rest/listings/types/{id}:
    get:
      summary: Get a listing type
      description: Gets a listing type by given ID.
      operationId: getRestListingsTypes
      x-api-path-slug: restlistingstypesid-get
      parameters:
      - in: path
        name: id
      - in: query
        name: with
        description: An array with child instances to be loaded
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Type
  /rest/orders/dates/types/{typeId}:
    get:
      summary: Find an order date type by it's ID
      description: Find an order date type by it's id.
      operationId: getRestOrdersDatesTypesType
      x-api-path-slug: restordersdatestypestypeid-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Find
      - Order
      - Date
      - Type
      - By
      - Its
      - ID
  /rest/orders/dates/types/{typeId}/names:
    get:
      summary: List names of an order date type
      description: Lists names in all languages available of an order date type. The
        ID of the date type must be specified.
      operationId: getRestOrdersDatesTypesTypeNames
      x-api-path-slug: restordersdatestypestypeidnames-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - List
      - Names
      - Of
      - Order
      - Date
      - Type
  /rest/orders/dates/types/{typeId}/names/{lang}:
    get:
      summary: Get a name of an order date type
      description: Gets a name of an order date type. The ID of the date type and
        the language of the name must be specified.
      operationId: getRestOrdersDatesTypesTypeNamesLang
      x-api-path-slug: restordersdatestypestypeidnameslang-get
      parameters:
      - in: path
        name: lang
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Name
      - Of
      - Order
      - Date
      - Type
  /rest/orders/documents/downloads/{type}:
    get:
      summary: Download documents of a document type
      description: Downloads documents of the same document type as a zip file. The
        type of the documents must be specified.
      operationId: getRestOrdersDocumentsDownloadsType
      x-api-path-slug: restordersdocumentsdownloadstype-get
      parameters:
      - in: query
        name: createdAtFrom
        description: Filter that restricts the search result to documents that were
          created on the specified date
      - in: query
        name: createdAtTo
        description: Filter that restricts the search result to documents that were
          created within a certain period of time
      - in: query
        name: displayDateFrom
        description: Filter that restricts the search result to documents that were
          displayed on the specified date
      - in: query
        name: displayDateTo
        description: Filter that restricts the search result to documents that were
          displayed within a certain period of time
      - in: query
        name: itemsPerPage
        description: The number of documents to display per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: plentyId
        description: The plenty ID of the order documents
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Download
      - Documents
      - Of
      - Document
      - Type
  /rest/orders/documents/{type}:
    get:
      summary: List documents of a type
      description: Lists documents of a type. The type must be specified.
      operationId: getRestOrdersDocumentsType
      x-api-path-slug: restordersdocumentstype-get
      parameters:
      - in: query
        name: createdAtFrom
        description: Filter that restricts the search result to documents that were
          created on the specified date
      - in: query
        name: createdAtTo
        description: Filter that restricts the search result to documents that were
          created within a certain period of time
      - in: query
        name: displayDateFrom
        description: Filter that restricts the search result to documents that were
          displayed on the specified date
      - in: query
        name: displayDateTo
        description: Filter that restricts the search result to documents that were
          displayed within a certain period of time
      - in: query
        name: itemsPerPage
        description: The items per page to search for
      - in: query
        name: page
        description: The page of results to search for
      - in: path
        name: type
      - in: query
        name: with
        description: Load additional relations for a document
      - in: query
        name: withContent
        description: Load also the document content as base64 encoded string
      responses:
        200:
          description: OK
      tags:
      - List
      - Documents
      - Of
      - Type
  /rest/orders/items/{orderItemId}/dates/{typeId}:
    delete:
      summary: Delete a date from an order item by order item and date type
      description: Deletest a date from an order item. The ID of the order item and
        the ID of the date type must be specified.
      operationId: deleteRestOrdersItemsOrderitemDatesType
      x-api-path-slug: restordersitemsorderitemiddatestypeid-delete
      parameters:
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Date
      - From
      - Order
      - Item
      - By
      - Order
      - Item
      - Date
      - Type
    get:
      summary: Get a date of an order item by order item and date type
      description: Gets a date of an order item. The ID of the order item and the
        ID of the date type must be specified.
      operationId: getRestOrdersItemsOrderitemDatesType
      x-api-path-slug: restordersitemsorderitemiddatestypeid-get
      parameters:
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Date
      - Of
      - Order
      - Item
      - By
      - Order
      - Item
      - Date
      - Type
    post:
      summary: Create a date for an order item by order item and date type
      description: Creates a date for an order item. The ID of the order item and
        the ID of the date type must be specified.
      operationId: postRestOrdersItemsOrderitemDatesType
      x-api-path-slug: restordersitemsorderitemiddatestypeid-post
      parameters:
      - in: body
        name: /rest/orders/items/{orderItemId}/dates/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Datean
      - Order
      - Item
      - By
      - Order
      - Item
      - Date
      - Type
    put:
      summary: Update a date of an order item by order item and date type
      description: Updates the date of an order item. The ID of the order item and
        the ID of the date type must be specified.
      operationId: putRestOrdersItemsOrderitemDatesType
      x-api-path-slug: restordersitemsorderitemiddatestypeid-put
      parameters:
      - in: body
        name: /rest/orders/items/{orderItemId}/dates/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Date
      - Of
      - Order
      - Item
      - By
      - Order
      - Item
      - Date
      - Type
  /rest/orders/items/{orderItemId}/properties/{typeId}:
    delete:
      summary: Delete an order item property by order item ID and order property type
        ID.
      description: Delete an order item property by order item id and order property
        type id..
      operationId: deleteRestOrdersItemsOrderitemPropertiesType
      x-api-path-slug: restordersitemsorderitemidpropertiestypeid-delete
      parameters:
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Item
      - Property
      - By
      - Order
      - Item
      - ID
      - Order
      - Property
      - Type
      - ID
    get:
      summary: Get an order item property by order item ID and order property type
        ID.
      description: Get an order item property by order item id and order property
        type id..
      operationId: getRestOrdersItemsOrderitemPropertiesType
      x-api-path-slug: restordersitemsorderitemidpropertiestypeid-get
      parameters:
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Item
      - Property
      - By
      - Order
      - Item
      - ID
      - Order
      - Property
      - Type
      - ID
    post:
      summary: Create an order item property by order item ID and order property type
        ID.
      description: Create an order item property by order item id and order property
        type id..
      operationId: postRestOrdersItemsOrderitemPropertiesType
      x-api-path-slug: restordersitemsorderitemidpropertiestypeid-post
      parameters:
      - in: body
        name: /rest/orders/items/{orderItemId}/properties/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Item
      - Property
      - By
      - Order
      - Item
      - ID
      - Order
      - Property
      - Type
      - ID
    put:
      summary: Update an order item property by order item ID and order property type
        ID.
      description: Update an order item property by order item id and order property
        type id..
      operationId: putRestOrdersItemsOrderitemPropertiesType
      x-api-path-slug: restordersitemsorderitemidpropertiestypeid-put
      parameters:
      - in: body
        name: /rest/orders/items/{orderItemId}/properties/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderItemId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Item
      - Property
      - By
      - Order
      - Item
      - ID
      - Order
      - Property
      - Type
      - ID
  /rest/orders/properties/types/{typeId}:
    delete:
      summary: Delete a property type.
      description: Deletes a property type and all names for it from the database.
        The ID of the type must be specified.
      operationId: deleteRestOrdersPropertiesTypesType
      x-api-path-slug: restorderspropertiestypestypeid-delete
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
    get:
      summary: Get a property type
      description: Gets a property type and its names in all languages. Optionally
        one or more languages can be specified to get a limited response.
      operationId: getRestOrdersPropertiesTypesType
      x-api-path-slug: restorderspropertiestypestypeid-get
      parameters:
      - in: query
        name: lang
        description: Languages to be loaded with the type model
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
    put:
      summary: Update a property type.
      description: Updates a property type and its names. The ID of the type must
        be specified. You can also create new names, if you provide data which does
        not yet exist.
      operationId: putRestOrdersPropertiesTypesType
      x-api-path-slug: restorderspropertiestypestypeid-put
      parameters:
      - in: body
        name: /rest/orders/properties/types/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
  /rest/orders/shipping/package_types/{shippingPackageTypeId}:
    get:
      summary: Get a shipping package type
      description: Gets a shipping package type. The ID of the shipping package type
        must be specified.
      operationId: getRestOrdersShippingPackageTypesShippingpackagetype
      x-api-path-slug: restordersshippingpackage-typesshippingpackagetypeid-get
      parameters:
      - in: path
        name: shippingPackageTypeId
      responses:
        200:
          description: OK
      tags:
      - Shipping
      - Package
      - Type
  /rest/orders/{orderId}/properties/{typeId}:
    delete:
      summary: Delete a property of an order by order ID and type ID
      description: Deletes a property of an order. The composite key of the property
        must be specified. The composite key is composed of the ID of the order and
        the ID of the order property type.
      operationId: deleteRestOrdersOrderPropertiesType
      x-api-path-slug: restordersorderidpropertiestypeid-delete
      parameters:
      - in: body
        name: /rest/orders/{orderId}/properties/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orderId
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Of
      - Order
      - By
      - Order
      - ID
      - Type
      - ID
  /rest/payment/properties/types/names:
    post:
      summary: Create a name of a property type
      description: Create a name of a property type.
      operationId: postRestPaymentPropertiesTypesNames
      x-api-path-slug: restpaymentpropertiestypesnames-post
      parameters:
      - in: body
        name: /rest/payment/properties/types/names
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Name
      - Of
      - Property
      - Type
    put:
      summary: Update a name of a property type
      description: Update a name of a property type.
      operationId: putRestPaymentPropertiesTypesNames
      x-api-path-slug: restpaymentpropertiestypesnames-put
      parameters:
      - in: body
        name: /rest/payment/properties/types/names
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Name
      - Of
      - Property
      - Type
  /rest/payment/properties/types/names/{nameId}:
    get:
      summary: Get a name of a property type
      description: Gets a name of a property type. The ID of the name must be specified.
      operationId: getRestPaymentPropertiesTypesNamesName
      x-api-path-slug: restpaymentpropertiestypesnamesnameid-get
      parameters:
      - in: path
        name: nameId
      responses:
        200:
          description: OK
      tags:
      - Name
      - Of
      - Property
      - Type
  /rest/payments/properties/types/{typeId}:
    get:
      summary: Get a property type
      description: Gets a property type. The ID of the type must be specified.
      operationId: getRestPaymentsPropertiesTypesType
      x-api-path-slug: restpaymentspropertiestypestypeid-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Type
  /rest/payments/property/{propertyTypeId}/{propertyValue}:
    get:
      summary: List payments by property type ID and value
      description: Lists all payments by the given property type ID and the value.
      operationId: getRestPaymentsPropertyPropertytypePropertyvalue
      x-api-path-slug: restpaymentspropertypropertytypeidpropertyvalue-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: path
        name: propertyTypeId
      - in: path
        name: propertyValue
      responses:
        200:
          description: OK
      tags:
      - List
      - Payments
      - By
      - Property
      - Type
      - ID
      - Value
  /rest/payments/transactions/{transactionTypeId}:
    get:
      summary: List payments of a transaction type
      description: Lists all payments of a transaction type. The ID of the transaction
        type must be specified.
      operationId: getRestPaymentsTransactionsTransactiontype
      x-api-path-slug: restpaymentstransactionstransactiontypeid-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: path
        name: transactionTypeId
      responses:
        200:
          description: OK
      tags:
      - List
      - Payments
      - Of
      - Transaction
      - Type
  /rest/stockmanagement/stock/types/{type}:
    get:
      summary: List stock by warehouse type
      description: Lists stock for all warehouses of the same warehouse type. The
        name of the type must be specified. Currently the only type available is 'sales'.
      operationId: getRestStockmanagementStockTypesType
      x-api-path-slug: reststockmanagementstocktypestype-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: type
      - in: query
        name: updatedAtFrom
        description: Filter that restricts the search result to stock that were last
          updated on the specified date
      - in: query
        name: updatedAtTo
        description: Filter that restricts the search result to stock that were last
          updated within a specified period of time
      - in: query
        name: variationId
        description: Filter that restricts the search result to stock with a variation
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - By
      - Warehouse
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