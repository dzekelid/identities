---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Delete My Follows Categories Entifier
  description: Delete my follows categories entifier.
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/follows/categories/{identifier}:
    delete:
      summary: Delete My Follows Categories Entifier
      description: Delete my follows categories entifier.
      operationId: deleteMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-delete
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
    get:
      summary: Get My Follows Categories Entifier
      description: Get my follows categories entifier.
      operationId: getMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-get
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
    post:
      summary: Post My Follows Categories Entifier
      description: Post my follows categories entifier.
      operationId: postMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-post
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
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