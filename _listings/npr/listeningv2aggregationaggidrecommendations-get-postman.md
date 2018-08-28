{
  "info": {
    "name": "NPR One API Reference",
    "_postman_id": "de0a00d2-f7b5-4579-95cd-2f1019175c02",
    "description": "NPR One is a smart application that brings the best of NPR and Member Station programming, newscasts, podcasts, and stories together to create a new experience for listening. It provides an editor-curated and localized mobile listening experience based on the content the listener chooses, likes, shares, and enjoys. The API provides all of the content and customization in a simple, structured way that is easy for applicationdevelopers to implement.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "1d14fc93-f2af-45f4-889a-f58e3cffef77",
          "name": "getAggRecommendations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.npr.org",
              "path": [
                "listening/v2/aggregation/:aggId/recommendations"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startNum",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "aggId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint provides a list of recent audio items associated with the aggregation along with metadata about the aggregation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b4680b2-b176-425d-aed2-21e9c1f4c09c"
            }
          ]
        }
      ]
    }
  ]
}