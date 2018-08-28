swagger: "2.0"
x-collection-name: Yapily
x-complete: 1
info:
  title: Yapily API
  description: to-access-endpoints-that-require-authentication-use-your-application-key-and-secret-created-in-the-dashboard-httpsdashboard-yapily-com
  version: 1.0.0
host: api.yapily.com:443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /identity:
    get:
      summary: Get identity
      description: Get identity.
      operationId: identityUsingGET
      x-api-path-slug: identity-get
      parameters:
      - in: header
        name: consent
        description: Consent Token
      responses:
        200:
          description: OK
      tags:
      - Identity