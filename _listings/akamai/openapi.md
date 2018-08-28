---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /prolexic-analytics/v1/metric-types:
    get:
      summary: List Metric Types
      description: List Metric Types
      operationId: prolexicanalyticsv1metrictypes
      x-api-path-slug: prolexicanalyticsv1metrictypes-get
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Metric
      - Types
---