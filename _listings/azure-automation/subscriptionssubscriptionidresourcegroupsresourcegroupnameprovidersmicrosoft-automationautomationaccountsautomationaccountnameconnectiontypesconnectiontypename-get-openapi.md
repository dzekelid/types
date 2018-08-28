---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Connection Type Get
  version: 1.0.0
  description: Retrieve the connectiontype identified by connectiontype name.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/modules/{moduleName}/objectDataTypes/{typeName}/fields
  : get:
      summary: Object Data Types List Fields By Module And Type
      description: Retrieve a list of fields of a given type identified by module
        name.
      operationId: ObjectDataTypes_ListFieldsByModuleAndType
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamemodulesmodulenameobjectdatatypestypenamefields-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: moduleName
        description: The name of module
      - in: query
        name: No Name
      - in: path
        name: typeName
        description: The name of type
      responses:
        200:
          description: OK
      tags:
      - Object
      - Data
      - Types
      - List
      - FieldsModuleType
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/objectDataTypes/{typeName}/fields
  : get:
      summary: Object Data Types List Fields By Type
      description: Retrieve a list of fields of a given type across all accessible
        modules.
      operationId: ObjectDataTypes_ListFieldsByType
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameobjectdatatypestypenamefields-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: typeName
        description: The name of type
      responses:
        200:
          description: OK
      tags:
      - Object
      - Data
      - Types
      - List
      - FieldsType
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/connectionTypes/{connectionTypeName}
  : delete:
      summary: Connection Type Delete
      description: Delete the connectiontype.
      operationId: ConnectionType_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypesconnectiontypename-delete
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: connectionTypeName
        description: The name of connectiontype
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Connection
      - Type
    get:
      summary: Connection Type Get
      description: Retrieve the connectiontype identified by connectiontype name.
      operationId: ConnectionType_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypesconnectiontypename-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: connectionTypeName
        description: The name of connectiontype
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Connection
      - Type
    put:
      summary: Connection Type Create Or Update
      description: Create a connectiontype.
      operationId: ConnectionType_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypesconnectiontypename-put
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: connectionTypeName
        description: The parameters supplied to the create or update connectiontype
          operation
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters supplied to the create or update connectiontype
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Connection
      - Type
      - Or
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/connectionTypes
  : get:
      summary: Connection Type List By Automation Account
      description: Retrieve a list of connectiontypes.
      operationId: ConnectionType_ListByAutomationAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnameconnectiontypes-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Connection
      - Type
      - List
      - Automation
      - Account
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