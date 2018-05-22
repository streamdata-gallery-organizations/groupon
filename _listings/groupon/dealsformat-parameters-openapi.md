---
swagger: "2.0"
x-collection-name: Groupon
x-complete: 0
info:
  title: Groupon Parameters Deals. Format
  description: Parameters deals. format.
  version: v2
host: api.groupon.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /status.{format}:
    parameters:
      summary: Parameters Status. Format
      description: Parameters status. format.
      operationId: parametersStatus.Format
      x-api-path-slug: statusformat-parameters
      responses:
        200:
          description: OK
      tags:
      - Status
      - Format
    get:
      summary: Get Status. Format
      description: Returns the status of Groupon's API and all the currently available
        versions of the API.
      operationId: getStatus.Format
      x-api-path-slug: statusformat-get
      responses:
        200:
          description: OK
      tags:
      - Status
      - Format
  /divisions.{format}:
    parameters:
      summary: Parameters Divisions. Format
      description: Parameters divisions. format.
      operationId: parametersDivisions.Format
      x-api-path-slug: divisionsformat-parameters
      responses:
        200:
          description: OK
      tags:
      - Divisions
      - Format
    get:
      summary: Get Divisions. Format
      description: Returns the list of all launched divisions.
      operationId: getDivisions.Format
      x-api-path-slug: divisionsformat-get
      responses:
        200:
          description: OK
      tags:
      - Divisions
      - Format
  /groupon_says.{format}:
    parameters:
      summary: Parameters Groupon Says. Format
      description: Parameters groupon says. format.
      operationId: parametersGrouponSays.Format
      x-api-path-slug: groupon-saysformat-parameters
      responses:
        200:
          description: OK
      tags:
      - Groupon
      - Says
      - Format
    get:
      summary: Get Groupon Says. Format
      description: Returns the list of recent (or random) Groupon Says commentaries.
      operationId: getGrouponSays.Format
      x-api-path-slug: groupon-saysformat-get
      responses:
        200:
          description: OK
      tags:
      - Groupon
      - Says
      - Format
  /deals/{id}.{format}:
    parameters:
      summary: Parameters Deals . Format
      description: Parameters deals . format.
      operationId: parametersDeals.Format
      x-api-path-slug: dealsidformat-parameters
      responses:
        200:
          description: OK
      tags:
      - Deals
      - Format
    get:
      summary: Get Deals . Format
      description: Returns the detailed information about a specified deal.
      operationId: getDeals.Format
      x-api-path-slug: dealsidformat-get
      responses:
        200:
          description: OK
      tags:
      - Deals
      - Format
  /deals.{format}:
    parameters:
      summary: Parameters Deals. Format
      description: Parameters deals. format.
      operationId: parametersDeals.Format
      x-api-path-slug: dealsformat-parameters
      responses:
        200:
          description: OK
      tags:
      - Deals
      - Format
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