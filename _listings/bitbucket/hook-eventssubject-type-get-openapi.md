---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Get Hook Events Subject Type
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
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /hook_events/{subject_type}:
    get:
      summary: Get Hook Events Subject Type
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
      operationId: getHookEventsSubjectType
      x-api-path-slug: hook-eventssubject-type-get
      parameters:
      - in: path
        name: subject_type
        description: A resource or subject type
      responses:
        200:
          description: OK
      tags:
      - Hook
      - Events
      - Subject
      - Type
    parameters:
      summary: Parameters Hook Events Subject Type
      description: Parameters hook events subject type
      operationId: parametersHookEventsSubjectType
      x-api-path-slug: hook-eventssubject-type-parameters
      responses:
        200:
          description: OK
      tags:
      - Hook
      - Events
      - Subject
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