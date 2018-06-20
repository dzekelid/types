---
name: HHS Media Services
x-slug: hhs-media-services
description: Use this API platform to create sites with text and multimedia content
  for syndication. CDC, FDA, HHS, and NIH have built syndication sites using this
  platform, which is available in Java and .NET.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Types
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/apis.md
specificationVersion: "0.14"
apis:
- name: HHS Media Services Get MediaTypes
  x-api-slug: hhs-media-services
  description: Returns the list of available MediaTypes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/mediaTypes.json
  tags: Resources,MediaTypes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/resourcesmediatypes-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/resourcesmediatypes-json-get-openapi.md
- name: HHS Media Services Get TagTypes
  x-api-slug: hhs-media-services
  description: Returns the list of TagTypes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/tags/tagTypes.json
  tags: Resources,Tags,TagTypes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/resourcestagstagtypes-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/resourcestagstagtypes-json-get-openapi.md
- name: HHS Media Services
  x-api-slug: hhs-media-services
  description: Use this API platform to create sites with text and multimedia content
    for syndication. CDC, FDA, HHS, and NIH have built syndication sites using this
    platform, which is available in Java and .NET.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2
  tags: Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/hhs-media-services/openapi.md
x-common:
- type: x-website
  url: https://api.digitalmedia.hhs.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---