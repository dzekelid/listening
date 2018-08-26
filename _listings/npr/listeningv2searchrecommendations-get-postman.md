{
  "info": {
    "name": "NPR Get a list of recent audio and aggregation items associated with search terms",
    "_postman_id": "d3855b8d-cd3b-4b38-a28e-1e18009dd02d",
    "description": "In the schema shown below, SearchItemDocument is not an actual type of returned object; the object returned by a search will be either an AggregationAudioItemListDocument or an AudioItemDocument.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "10cac420-ad72-4d01-9d1a-dfa0cf63b245",
          "name": "getSearchRecommendations",
          "request": {
            "url": "http://api.npr.org/listening/v2/search/recommendations?No Name=%7B%7D&searchTerms=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "In the schema shown below, SearchItemDocument is not an actual type of returned object; the object returned by a search will be either an AggregationAudioItemListDocument or an AudioItemDocument"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "584fe2d2-7971-4ffc-b26b-7b87d3795918"
            }
          ]
        }
      ]
    }
  ]
}