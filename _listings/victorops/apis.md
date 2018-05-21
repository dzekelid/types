---
name: VictorOps
x-slug: victorops
description: VictorOps is a hub for centralizing the flow of information throughout
  the incident lifecycle. Driven by IT and DevOps system data, VictorOps provides
  a unified platform for real-time alerting, collaboration, and documentation. Using
  VictorOps, teams resolve incidents faster to help minimize the impact of downtime
  and speed innovation.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/victorops.jpg
x-kinRank: "8"
x-alexaRank: ""
tags: Types
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apis.md
specificationVersion: "0.14"
apis:
- name: VictorOps Get the available contact types
  x-api-slug: victorops
  description: |-
    Get the available contact types

    description: "Email Address", type: "email"
    description: "Phone Number", type: "phone"

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/victorops.jpg
  humanURL: https://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/contacts
  tags: Continuous Deployment,Continuous Integration,Orchestration,Api-public,V1,Policies,Types,Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypescontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypescontacts-get-openapi.md
- name: VictorOps Get the available notification types
  x-api-slug: victorops
  description: |-
    Get the available notification types

    description: "Send a push notification to all my devices", type: "push"
    description: "Send an email to an email address", type: "email"
    description: "Send an SMS to a phone number", type: "sms"
    description: "Make a phone call to a phone number", type: "phone"

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/victorops.jpg
  humanURL: https://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/notifications
  tags: Continuous Deployment,Continuous Integration,Orchestration,Api-public,V1,Policies,Types,Notifications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypesnotifications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypesnotifications-get-openapi.md
- name: VictorOps Get the available timeout values
  x-api-slug: victorops
  description: |-
    Get the available timeout values

    description: "If still unacked after 1 minute", type: 1
    description: "If still unacked after 5 minutes", type: 5
    description: "If still unacked after 10 minutes", type: 10
    description: "If still unacked after 15 minutes", type: 15
    description: "If still unacked after 20 minutes", type: 20
    description: "If still unacked after 25 minutes", type: 25
    description: "If still unacked after 30 minutes", type: 30
    description: "If still unacked after 45 minutes", type: 45
    description: "If still unacked after 60 minutes", type: 60

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/victorops.jpg
  humanURL: https://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/timeouts
  tags: Continuous Deployment,Continuous Integration,Orchestration,Api-public,V1,Policies,Types,Timeouts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypestimeouts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/apipublicv1policiestypestimeouts-get-openapi.md
- name: VictorOps
  x-api-slug: victorops
  description: VictorOps is a hub for centralizing the flow of information throughout
    the incident lifecycle. Driven by IT and DevOps system data, VictorOps provides
    a unified platform for real-time alerting, collaboration, and documentation. Using
    VictorOps, teams resolve incidents faster to help minimize the impact of downtime
    and speed innovation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/victorops.jpg
  humanURL: https://victorops.com
  baseURL: https://api.victorops.com//
  tags: Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/victorops/openapi.md
x-common:
- type: x-blog
  url: https://victorops.com/blog/
- type: x-blog-rss
  url: https://victorops.com/feed/
- type: x-github
  url: https://github.com/victorops
- type: x-pricing
  url: https://victorops.com/pricing/
- type: x-twitter
  url: https://twitter.com/VictorOps
- type: x-website
  url: https://victorops.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---