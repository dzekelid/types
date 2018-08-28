---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket - Get Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-get
  description: |-
    Returns a paginated list of all valid webhook events for the
    specified entity.

    This is public data that does not require any scopes or authentication.

    Example:

    NOTE: The following example is a truncated response object for the `team` `subject_type`.
    We return the same structure for the other `subject_type` objects.

    ```
    $ curl https://api.bitbucket.org/2.0/hook_events/team
    {
        "page": 1,
        "pagelen": 30,
        "size": 21,
        "values": [
            {
                "category": "Repository",
                "description": "Whenever a repository push occurs",
                "event": "repo:push",
                "label": "Push"
            },
            {
                "category": "Repository",
                "description": "Whenever a repository fork occurs",
                "event": "repo:fork",
                "label": "Fork"
            },
            ...
            {
                "category": "Repository",
                "description": "Whenever a repository import occurs",
                "event": "repo:imported",
                "label": "Import"
            }
        ]
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-openapi.md
- name: Bitbucket - Parameters Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-parameters
  description: Parameters hook events subject type
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-openapi.md
- name: Bitbucket - Parameters Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-parameters
  description: Parameters hook events subject type
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-openapi.md
- name: Bitbucket - Parameters Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-parameters
  description: Parameters hook events subject type
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-parameters-openapi.md
- name: Bitbucket - Get Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-get
  description: |-
    Returns a paginated list of all valid webhook events for the
    specified entity.

    This is public data that does not require any scopes or authentication.

    Example:

    NOTE: The following example is a truncated response object for the `team` `subject_type`.
    We return the same structure for the other `subject_type` objects.

    ```
    $ curl https://api.bitbucket.org/2.0/hook_events/team
    {
        "page": 1,
        "pagelen": 30,
        "size": 21,
        "values": [
            {
                "category": "Repository",
                "description": "Whenever a repository push occurs",
                "event": "repo:push",
                "label": "Push"
            },
            {
                "category": "Repository",
                "description": "Whenever a repository fork occurs",
                "event": "repo:fork",
                "label": "Fork"
            },
            ...
            {
                "category": "Repository",
                "description": "Whenever a repository import occurs",
                "event": "repo:imported",
                "label": "Import"
            }
        ]
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-openapi.md
- name: Bitbucket - Get Hook Events Subject Type
  x-api-slug: hook-eventssubject-type-get
  description: |-
    Returns a paginated list of all valid webhook events for the
    specified entity.

    This is public data that does not require any scopes or authentication.

    Example:

    NOTE: The following example is a truncated response object for the `team` `subject_type`.
    We return the same structure for the other `subject_type` objects.

    ```
    $ curl https://api.bitbucket.org/2.0/hook_events/team
    {
        "page": 1,
        "pagelen": 30,
        "size": 21,
        "values": [
            {
                "category": "Repository",
                "description": "Whenever a repository push occurs",
                "event": "repo:push",
                "label": "Push"
            },
            {
                "category": "Repository",
                "description": "Whenever a repository fork occurs",
                "event": "repo:fork",
                "label": "Fork"
            },
            ...
            {
                "category": "Repository",
                "description": "Whenever a repository import occurs",
                "event": "repo:imported",
                "label": "Import"
            }
        ]
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/bitbucket/hook-eventssubject-type-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bigoven.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bitbucket.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitbucket
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: http://bitbucket.org
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---