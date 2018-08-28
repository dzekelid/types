---
name: WebTRIS
x-slug: webtris
description: The WebTRIS data available at http://webtris.highwaysengland.co.uk/ is
  available via an application programming interface (API) in JSON format. This is
  a free service and there is no need to register to use it. Developers can utilise
  the WebTRIS data to provide their own services, applications and websites.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/webtris-traffic-flow-api.png
x-kinRank: "7"
x-alexaRank: ""
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/webtris/apis.md
specificationVersion: "0.14"
apis:
- name: ' - Return list of site types'
  x-api-slug: vversionsitetypes-get
  description: Return list of site types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/webtris-traffic-flow-api.png
  humanURL: http://webtris.highwaysengland.co.uk/
  baseURL: https://webtris.highwaysengland.co.uk//api
  tags: Traffic, Transportation, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/webtris/vversionsitetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/webtris/vversionsitetypes-get-openapi.md
x-common:
- type: x-documentation
  url: http://webtris.highwaysengland.co.uk/api/swagger/ui/index
- type: x-website
  url: http://webtris.highwaysengland.co.uk/
- type: x-api-gallery
  url: http://weatherbit.io.api.gallery.streamdata.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---