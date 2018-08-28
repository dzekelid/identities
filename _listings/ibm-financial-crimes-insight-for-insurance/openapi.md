swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 1
info:
  title: Financial Crimes Insight for Insurance public REST APIs
  description: these-are-the-financial-crimes-insight-for-insurance-public-rest-apis-used-by-clients-to-access-the-fcii-capabilities
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