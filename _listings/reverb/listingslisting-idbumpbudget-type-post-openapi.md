---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Post Listings Listing Bump Budget Type
  description: Post listings listing bump budget type.
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /categories/{product_type}/{category}:
    get:
      summary: Get Categories Product Type Category
      description: Get categories product type category.
      operationId: getCategoriesProductTypeCategory
      x-api-path-slug: categoriesproduct-typecategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: product_type
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Product
      - Type
      - Category
  /listings/{listing_id}/bump/{budget_type}:
    post:
      summary: Post Listings Listing Bump Budget Type
      description: Post listings listing bump budget type.
      operationId: postListingsListingBumpBudgetType
      x-api-path-slug: listingslisting-idbumpbudget-type-post
      parameters:
      - in: path
        name: budget_type
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Bump
      - Budget
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