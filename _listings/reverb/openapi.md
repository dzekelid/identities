swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
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