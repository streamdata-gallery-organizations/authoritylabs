---
swagger: "2.0"
x-collection-name: AuthorityLabs
x-complete: 0
info:
  title: Authority Labs Partner API Delayed Queue
  description: Delayed Queue
  termsOfService: http://authoritylabs.com/terms/
  version: v1
host: api.authoritylabs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /keywords:
    post:
      summary: Delayed Queue
      description: Delayed Queue
      operationId: delayed-queue
      x-api-path-slug: keywords-post
      responses:
        200:
          description: OK
      tags:
      - Keywords
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