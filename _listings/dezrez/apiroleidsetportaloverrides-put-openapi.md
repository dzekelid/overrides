---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set portal configuration exclusivity overrides
  version: 1.0.0
  description: Set portal configuration exclusivity overrides.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/role/{id}/setportaloverrides:
    put:
      summary: Set portal configuration exclusivity overrides
      description: Set portal configuration exclusivity overrides.
      operationId: Role_SetPortalConfigurationDelayOverridesByidBydatacontract
      x-api-path-slug: apiroleidsetportaloverrides-put
      parameters:
      - in: body
        name: datacontract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Portal
      - Configuration
      - Exclusivity
      - Overrides
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