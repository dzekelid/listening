---
name: NPR
x-slug: npr
description: NPR delivers breaking national and world news. Also top stories from
  business, politics, health, science, technology, music, arts and culture. Subscribe
  to podcasts and RSS feeds.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
x-kinRank: "9"
x-alexaRank: "598"
tags: Listening
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/apis.md
specificationVersion: "0.14"
apis:
- name: NPR One API Reference - Get a set of recommendations for an aggregation
  x-api-slug: listeningv2aggregationaggidrecommendations-get
  description: This endpoint provides a list of recent audio items associated with
    the aggregation along with metadata about the aggregation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2aggregationaggidrecommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2aggregationaggidrecommendations-get-openapi.md
- name: NPR One API Reference - Get the list of available channels
  x-api-slug: listeningv2channels-get
  description: These channels allow the user to specify a focus for the content returned
    in the recommendations endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2channels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2channels-get-openapi.md
- name: NPR One API Reference - Get a list of recommendations from a category of content
    from an organization
  x-api-slug: listeningv2organizationsorgidcategoriescategoryrecommendations-get
  description: This endpoint provides a list of recommendations from a category of
    content from  an organization.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2organizationsorgidcategoriescategoryrecommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2organizationsorgidcategoriescategoryrecommendations-get-openapi.md
- name: NPR One API Reference - Get a variety of details about an organization including
    various lists of recent audio items
  x-api-slug: listeningv2organizationsorgidrecommendations-get
  description: This endpoint provides a variety of details about an organization including
    various lists of recent audio items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2organizationsorgidrecommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2organizationsorgidrecommendations-get-openapi.md
- name: NPR One API Reference - Retrieve the most recent promo audio heard by the
    logged-in user
  x-api-slug: listeningv2promorecommendations-get
  description: Gets the most recently played promo for which the user has neither
    tapped through the promo or listened to the target story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2promorecommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2promorecommendations-get-openapi.md
- name: NPR One API Reference - Get a list of media for the logged-in user from NPR's
    recommendation engine
  x-api-slug: listeningv2recommendations-get
  description: |-
    This endpoint returns a list of audio recommendations. It is designed to be used for an initial list of recommendations, and then `GET /listening/v2/ratings?recommend=true` should be used for subsequent requests for recommendations.

    A fully-populated link to the ratings endpoint is returned with each individual recommendation and is located in the AudioItemDocument under the `links['recommendations']` object. The query parameters in this link should not be modified.
    Be sure to copy and send back the entire ratings object (RatingData), as new fields may be added to it in the future.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2recommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2recommendations-get-openapi.md
- name: NPR One API Reference - Get a list of recent audio and aggregation items associated
    with search terms
  x-api-slug: listeningv2searchrecommendations-get
  description: In the schema shown below, SearchItemDocument is not an actual type
    of returned object; the object returned by a search will be either an AggregationAudioItemListDocument
    or an AudioItemDocument.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2searchrecommendations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/listening/master/_listings/npr/listeningv2searchrecommendations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://nfusion.solutions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://npr.stack.network
- type: x-base
  url: http://api.npr.org/
- type: x-codecademy
  url: http://www.codecademy.com/tracks/npr
- type: x-crunchbase
  url: https://crunchbase.com/organization/npr
- type: x-crunchbase
  url: http://www.crunchbase.com/company/npr
- type: x-developer
  url: http://dev.npr.org/
- type: x-documentation
  url: http://dev.npr.org/#accessing-the-api
- type: x-email
  url: permissions@npr.org
- type: x-email
  url: ogcstaff@npr.org
- type: x-email
  url: employment@npr.org
- type: x-email
  url: careers@npr.org
- type: x-email
  url: kroc@npr.org
- type: x-email
  url: mediarelations@npr.org
- type: x-email
  url: sponsorship@npr.org
- type: x-email
  url: ashamblin@npr.org
- type: x-email
  url: giving@npr.org
- type: x-email
  url: giftplanning@npr.org
- type: x-email
  url: NPRDonorCommunications@npr.org
- type: x-getting-started
  url: http://dev.npr.org/#quick-start
- type: x-github
  url: https://github.com/npr
- type: x-selfservice-registration
  url: http://www.npr.org/templates/reg/
- type: x-terms-of-service
  url: http://www.npr.org/about-npr/179876898/terms-of-use
- type: x-twitter
  url: https://twitter.com/NPR
- type: x-twitter
  url: https://twitter.com/NPRTechTeam
- type: x-website
  url: http://npr.org
- type: x-website
  url: http://www.npr.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---