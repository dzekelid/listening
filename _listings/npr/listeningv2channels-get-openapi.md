---
swagger: "2.0"
x-collection-name: NPR
x-complete: 0
info:
  title: NPR Get the list of available channels
  description: These channels allow the user to specify a focus for the content returned
    in the recommendations endpoint.
  termsOfService: http://dev.npr.org/develop/terms-of-use
  contact:
    name: NPR One Enterprise Team
    url: http://dev.npr.org
    email: NPROneEnterprise@npr.org
  version: 1.0.0
host: api.npr.org
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /listening/v2/aggregation/{aggId}/recommendations:
    get:
      summary: Get a set of recommendations for an aggregation
      description: This endpoint provides a list of recent audio items associated
        with the aggregation along with metadata about the aggregation.
      operationId: getAggRecommendations
      x-api-path-slug: listeningv2aggregationaggidrecommendations-get
      parameters:
      - in: path
        name: aggId
        description: ID of an aggregation such as a program or podcast
      - in: query
        name: No Name
      - in: query
        name: startNum
        description: The result to start with
      responses:
        200:
          description: OK
      tags:
      - News
      - Listening
      - Aggregation
      - Agg
      - Recommendations
  /listening/v2/channels:
    get:
      summary: Get the list of available channels
      description: These channels allow the user to specify a focus for the content
        returned in the recommendations endpoint.
      operationId: getChannels
      x-api-path-slug: listeningv2channels-get
      parameters:
      - in: query
        name: exploreOnly
        description: If set to `true`, this call will return only channels that should
          be shown in the clients `Explore` view
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - Listening
      - Channels
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