---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Get Enterprise Metadata
  description: Used to retrieve all metadata templates within a user's enterprise.
    Currently only the enterprise scope is supported.
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metadata_templates/{SCOPE}:
    get:
      summary: Get Enterprise Metadata
      description: Used to retrieve all metadata templates within a user's enterprise.
        Currently only the enterprise scope is supported.
      operationId: getEnterpriseMetadataTemplates
      x-api-path-slug: metadata-templatesscope-get
      parameters:
      - in: path
        name: SCOPE
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Metadata
      - Templates
      - Scope
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