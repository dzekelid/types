---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 1
info:
  title: DataLakeAnalyticsJobManagementClient
  description: creates-an-azure-data-lake-analytics-job-client-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tabletypes:
    get:
      summary: Catalog List Table Types
      description: Retrieves the list of table types from the Data Lake Analytics
        catalog.
      operationId: Catalog_ListTableTypes
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametabletypes-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table types
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table types
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Types
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/types:
    get:
      summary: Catalog List Types
      description: Retrieves the list of types within the specified database and schema
        from the Data Lake Analytics catalog.
      operationId: Catalog_ListTypes
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametypes-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the types
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the types
      responses:
        200:
          description: OK
      tags:
      - Catalog Types
---