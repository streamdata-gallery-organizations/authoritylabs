swagger: "2.0"
x-collection-name: AuthorityLabs
x-complete: 1
info:
  title: AuthorityLabs Partner API
  description: the-partner-api-should-be-used-when-you-only-require-search-results-and-is-different-from-our-standard-interface-accounts--pricing-is-based-on-specific-endpoint-usage-per-thousand-calls-
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
  /keywords/priority:
    post:
      summary: Priority Queue
      description: Priority Queue
      operationId: priority-queue
      x-api-path-slug: keywordspriority-post
      responses:
        200:
          description: OK
      tags:
      - Keywords
      - Priority
  /keywords/{keyword}:
    get:
      summary: Search Results
      description: Search Results
      operationId: search-results
      x-api-path-slug: keywordskeyword-get
      parameters:
      - in: path
        name: keyword
      responses:
        200:
          description: OK
      tags:
      - Keywords
      - Keyword