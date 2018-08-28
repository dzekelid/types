---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Get all order types for a merchant
  version: 1.0.0
  description: Merchants have the ability to create custom order types via the Setup
    App (https://www.clover.com/setupapp). These custom order types can be associated
    with a System Order Type (see /v3/merchants/{mId}/system_order_types). Custom
    Order Types can support items in all categories (filterCategories=false) or a
    subset of the merchant's categories (filterCategories=true and categories property
    contains the list of supported categories). Note that when expanding the categories
    for an order type, they will only be returned if this orderType only supports
    a subset of the categories (filterCategories=true). If the orderType supports
    all categories (filterCategories=false) then you should make a GET request to
    /v3/merchants/{mId}/categories.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/order_types:
    get:
      summary: Get all order types for a merchant
      description: Merchants have the ability to create custom order types via the
        Setup App (https://www.clover.com/setupapp). These custom order types can
        be associated with a System Order Type (see /v3/merchants/{mId}/system_order_types).
        Custom Order Types can support items in all categories (filterCategories=false)
        or a subset of the merchant's categories (filterCategories=true and categories
        property contains the list of supported categories). Note that when expanding
        the categories for an order type, they will only be returned if this orderType
        only supports a subset of the categories (filterCategories=true). If the orderType
        supports all categories (filterCategories=false) then you should make a GET
        request to /v3/merchants/{mId}/categories.
      operationId: GetOrderTypes
      x-api-path-slug: v3merchantsmidorder-types-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [hours, attributes, categories]'
      - in: query
        name: filter
        description: 'Filter fields: [id, deletedTime]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Order
      - Types
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