---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: Jira Cloud REST API - Get issue link types
  x-api-slug: api2issuelinktype-get
  description: Returns a list of available issue link types, if issue linking is enabled.
    Each issue link type has an id, a name and a label for the outward and inward
    link relationship.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-get-openapi.md
- name: Jira Cloud REST API - Get alternative issue types
  x-api-slug: api2issuetypeidalternatives-get
  description: Returns a list of issue types that can be used to replace the issue
    type. The alternative issue types are those assigned to the same workflow scheme,
    field configuration scheme, and screen scheme. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidalternatives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidalternatives-get-openapi.md
- name: Jira Cloud REST API - Get all project types
  x-api-slug: api2projecttype-get
  description: |-
    Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttype-get-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Create issue
  x-api-slug: api2issue-post
  description: |-
    Creates an issue or a sub-task from a JSON representation.

    You can provide two parameters in request's body: `update` or `fields`. The fields, that can be set on an issue create operation, can be determined using the **/rest/api/2/issue/createmeta** resource. If a particular field is not configured to appear on the issue's Create screen, then it will not be returned in the createmeta response. A field validation error will occur if such field is submitted in request.

    Creating a sub-task is similar to creating an issue with the following differences:

    *   `issueType` field must be set to a sub-task issue type (use `/issue/createmeta` to find sub-task issue types), and
    *   You must provide a `parent` field with the ID or key of the parent issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issue-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issue-post-openapi.md
- name: Jira Cloud REST API - Get issue link types
  x-api-slug: api2issuelinktype-get
  description: Returns a list of available issue link types, if issue linking is enabled.
    Each issue link type has an id, a name and a label for the outward and inward
    link relationship.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-get-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/atlassian/api2issuelinktype-post-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---