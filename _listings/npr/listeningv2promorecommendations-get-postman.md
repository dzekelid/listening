{
  "info": {
    "name": "NPR Retrieve the most recent promo audio heard by the logged-in user",
    "_postman_id": "3c0f4fc8-3044-475a-a53d-5e55bb2216f5",
    "description": "Gets the most recently played promo for which the user has neither tapped through the promo or listened to the target story.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "daa13555-6455-48e0-9c86-3b0fa0cefbcd",
          "name": "getPromo",
          "request": {
            "url": "http://api.npr.org/listening/v2/promo/recommendations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the most recently played promo for which the user has neither tapped through the promo or listened to the target story"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9465c5b0-3e6e-47fd-a29e-9ad9e9ce0243"
            }
          ]
        }
      ]
    }
  ]
}