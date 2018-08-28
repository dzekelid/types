---
name: Clover
x-slug: clover
description: Clover, a First Data company, builds the largest open-architecture point
  of sale solution aimed at small &amp; medium sized business owners. Our products
  are changing the consumer/merchant experience for the better, opening avenues for
  seamless customer-merchant interactions. There are five versions of Clover, including
  the Clover Station, Clover Mobile, Clover Mini, Clover Go, and Clover Flex. With
  Clover, First Data is aiming to create the largest open architecture operating system
  for commerce-enabling solutions and applications for business owners.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
x-kinRank: "7"
x-alexaRank: "23096"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/apis.md
specificationVersion: "0.14"
apis:
- name: ' - Get all order types for a merchant'
  x-api-slug: v3merchantsmidorder-types-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-types-get-openapi.md
- name: ' - Create Order Type For Merchant'
  x-api-slug: v3merchantsmidorder-types-post
  description: Create order type for merchant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-types-post-openapi.md
- name: ' - Get a single order type'
  x-api-slug: v3merchantsmidorder-typesordertypeid-get
  description: Get a single order type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-typesordertypeid-get-openapi.md
- name: ' - Update a single order type'
  x-api-slug: v3merchantsmidorder-typesordertypeid-post
  description: Update a single order type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-typesordertypeid-post-openapi.md
- name: ' - Delete an order type'
  x-api-slug: v3merchantsmidorder-typesordertypeid-delete
  description: Delete an order type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-typesordertypeid-delete-openapi.md
- name: ' - Return a list of system order types'
  x-api-slug: v3merchantsmidsystem-order-types-get
  description: Merchants can create custom Order Types via "/v3/merchants/{mId}/order_types".
    It is useful to associate these custom order types with particular system order
    types in order to group things functionally. For example, a merchant may have
    a "Lunch Take-Out" order type and a "Dinner Take-Out" order type. These two order
    types can be associated with the "TAKE-OUT-TYPE" system order type so that applications
    can understand that they are both take-out order types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidsystem-order-types-get-openapi.md
- name: ' - Create or delete a order type category'
  x-api-slug: v3merchantsmidorder-type-categories-post
  description: Create or delete a order type category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-type-categories-post-openapi.md
- name: ' - Create or delete a order type category'
  x-api-slug: v3merchantsmidorder-type-categories-post
  description: Create or delete a order type category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-type-categories-post-openapi.md
- name: ' - Create or delete a order type category'
  x-api-slug: v3merchantsmidorder-type-categories-post
  description: Create or delete a order type category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/clover/v3merchantsmidorder-type-categories-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://cloudflare.api.gallery.streamdata.io
- type: x-api-stack
  url: http://clover.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/clover
- type: x-developer
  url: https://www.clover.com/developers
- type: x-documentation
  url: https://docs.clover.com/
- type: x-github
  url: https://github.com/clover
- type: x-twitter
  url: https://twitter.com/CloverPOS
- type: x-website
  url: https://www.clover.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---