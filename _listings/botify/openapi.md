swagger: "2.0"
x-collection-name: Botify
x-complete: 1
info:
  title: Botify
  description: botify-saas-api
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{username}/{project_slug}/filters/{identifier}:
    get:
      summary: Get Projects Username Project Slug Filters Entifier
      description: Retrieves a specific saved filter's name, ID and filter value
      operationId: getProjectsUsernameProjectSlugFiltersEntifier
      x-api-path-slug: projectsusernameproject-slugfiltersidentifier-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
      - Identifier
    parameters:
      summary: Parameters Projects Username Project Slug Filters Entifier
      description: Parameters projects username project slug filters entifier.
      operationId: parametersProjectsUsernameProjectSlugFiltersEntifier
      x-api-path-slug: projectsusernameproject-slugfiltersidentifier-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
      - Identifier