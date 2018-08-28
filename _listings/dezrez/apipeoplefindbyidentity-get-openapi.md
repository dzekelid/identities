---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Gets the person by an identity reference
  version: 1.0.0
  description: Gets the person by an identity reference.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/identity/Get:
    get:
      summary: Gets all of the identities for the logged in person
      description: Gets all of the identities for the logged in person.
      operationId: Identity_GetLoggedInPersonIdentities
      x-api-path-slug: apiidentityget-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Of
      - Identitiesthe
      - Logged
      - In
      - Person
  /api/identity/Add:
    post:
      summary: Adds a new identity (E.g. Facebook Identity, Twitter identity etc.)
        to a person
      description: Adds a new identity (e.g. facebook identity, twitter identity etc.)
        to a person.
      operationId: Identity_AddIdentityToPersonBypersonIdByidentity
      x-api-path-slug: apiidentityadd-post
      parameters:
      - in: body
        name: identity
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Identity
      - (E
      - G
      - ""
      - Facebook
      - Identity
      - ""
      - Twitter
      - Identity
      - Etc
      - )
      - To
      - Person
  /api/identity/Remove:
    put:
      summary: Removes an identity (E.g. Facebook Identity, Twitter identity etc.)
        from a person
      description: Removes an identity (e.g. facebook identity, twitter identity etc.)
        from a person.
      operationId: Identity_RemoveIdentityFromPersonBypersonIdByidentityId
      x-api-path-slug: apiidentityremove-put
      parameters:
      - in: query
        name: identityId
      - in: query
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Removes
      - Identity
      - (E
      - G
      - ""
      - Facebook
      - Identity
      - ""
      - Twitter
      - Identity
      - Etc
      - )
      - From
      - Person
  /api/people/findbyidentity:
    get:
      summary: Gets the person by an identity reference
      description: Gets the person by an identity reference.
      operationId: People_GetPersonByIdentityByissuerBynameidentifier
      x-api-path-slug: apipeoplefindbyidentity-get
      parameters:
      - in: query
        name: issuer
        description: The issuer of the identity
      - in: query
        name: nameidentifier
        description: The nameidentifier of the identity
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Person
      - By
      - Identity
      - Reference
  /api/sync/cronofycallback/{negotiatorId}/{uniqueIdentifier}:
    post:
      summary: Forces a call to get updates from Cronofy for the rezi calendar
      description: Forces a call to get updates from cronofy for the rezi calendar.
      operationId: Sync_CronofyCallbackBynegotiatorIdByuniqueIdentifierBycalendarSyncResyncDataContract
      x-api-path-slug: apisynccronofycallbacknegotiatoriduniqueidentifier-post
      parameters:
      - in: body
        name: calendarSyncResyncDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: negotiatorId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: uniqueIdentifier
      responses:
        200:
          description: OK
      tags:
      - Forces
      - Call
      - To
      - Get
      - Updates
      - From
      - Cronofythe
      - Rezi
      - Calendar
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