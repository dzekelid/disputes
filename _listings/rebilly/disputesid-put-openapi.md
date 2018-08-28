---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Create or update a Dispute with predefined ID
  description: Create or update a Dispute with predefined identifier string
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /disputes:
    get:
      summary: Retrieve a list of disputes
      description: Retrieve a list of disputes
      operationId: disputes.get
      x-api-path-slug: disputes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Disputes
    post:
      summary: Create a dispute
      description: Create a dispute
      operationId: disputes.post
      x-api-path-slug: disputes-post
      parameters:
      - in: body
        name: body
        description: Dispute resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Dispute
  /disputes/{id}:
    get:
      summary: Retrieve a dispute
      description: Retrieve a dispute with specified identifier string
      operationId: disputes.id.get
      x-api-path-slug: disputesid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Dispute
    put:
      summary: Create or update a Dispute with predefined ID
      description: Create or update a Dispute with predefined identifier string
      operationId: disputes.id.put
      x-api-path-slug: disputesid-put
      parameters:
      - in: body
        name: body
        description: Dispute resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Update
      - Dispute
      - Predefined
      - ID
  /disputes/{id}/matched-rules:
    get:
      summary: Get matched rules for the dispute
      description: Get matched rules for the dispute
      operationId: disputes.id.matched_rules.get
      x-api-path-slug: disputesidmatchedrules-get
      responses:
        200:
          description: OK
      tags:
      - Matched
      - Rulesthe
      - Dispute
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