swagger: "2.0"
x-collection-name: AWS ElastiCache
x-complete: 1
info:
  title: AWS ElastiCache API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListAvailableNodeTypes:
    get:
      summary: List Available Node Types
      description: .
      operationId: listAvailableNodeTypes
      x-api-path-slug: actionlistavailablenodetypes-get
      parameters:
      - in: query
        name: AvailableNodeTypes.member.N
        description: 'Type: array of AvailableNodeType objects'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Node Types
  /?Action=ListAllowedNodeTypeModifications:
    get:
      summary: List Allowed Node Type Modifications
      description: |-
        Lists all available node types that you
                    can scale your Redis cluster's or replication group's current node type up to.
      operationId: listAllowedNodeTypeModifications
      x-api-path-slug: actionlistallowednodetypemodifications-get
      parameters:
      - in: query
        name: CacheClusterId
        description: The name of the cache cluster you want to scale up to a larger
          node instanced type
        type: string
      - in: query
        name: ReplicationGroupId
        description: The name of the replication group want to scale up to a larger
          node type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Node Type Modifications