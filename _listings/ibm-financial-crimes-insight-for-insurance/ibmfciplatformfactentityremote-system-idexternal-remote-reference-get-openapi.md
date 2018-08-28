---
swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 0
info:
  title: IBM Financial Crimes Insight for Insurance API Retrieve set of identities
    considered to be the same entity
  description: This method is used to retrieve the set of individuals (or organizations)
    that are considered the same as the provided party reference
  version: 1.0.0
host: fcihost.ibm.com:9443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ibm/fci/platform/fact/entity/{remote_system_id}/{external_remote_reference}:
    get:
      summary: Retrieve set of identities considered to be the same entity
      description: This method is used to retrieve the set of individuals (or organizations)
        that are considered the same as the provided party reference
      operationId: getResolvedEntityByRef
      x-api-path-slug: ibmfciplatformfactentityremote-system-idexternal-remote-reference-get
      parameters:
      - in: path
        name: external_remote_reference
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: remote_system_id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Set
      - Of
      - Identities
      - Considered
      - To
      - Be
      - Same
      - Entity
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