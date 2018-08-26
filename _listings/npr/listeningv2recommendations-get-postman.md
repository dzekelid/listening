{
  "info": {
    "name": "NPR Get a list of media for the logged-in user from NPR's recommendation engine",
    "_postman_id": "c537efc2-1435-4916-9365-da346c45e607",
    "description": "This endpoint returns a list of audio recommendations. It is designed to be used for an initial list of recommendations, and then `GET /listening/v2/ratings?recommend=true` should be used for subsequent requests for recommendations.\n\nA fully-populated link to the ratings endpoint is returned with each individual recommendation and is located in the AudioItemDocument under the `links['recommendations']` object. The query parameters in this link should not be modified.\nBe sure to copy and send back the entire ratings object (RatingData), as new fields may be added to it in the future.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "7d852b0e-3f16-4111-a019-c21206d4b131",
          "name": "getRecommendations",
          "request": {
            "url": "http://api.npr.org/listening/v2/recommendations?No Name=%7B%7D&notifiedMediaId=%7B%7D&sharedMediaId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint returns a list of audio recommendations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0710761d-047b-4422-939f-496e8223aba9"
            }
          ]
        }
      ]
    }
  ]
}