{
  "info": {
    "name": "NPR Get the list of available channels",
    "_postman_id": "8258adf7-d270-42fe-bd6a-d68e920fab98",
    "description": "These channels allow the user to specify a focus for the content returned in the recommendations endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "fc329bdd-7c6b-44de-a2ad-2541ceed9f3f",
          "name": "getChannels",
          "request": {
            "url": "http://api.npr.org/listening/v2/channels?exploreOnly=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "These channels allow the user to specify a focus for the content returned in the recommendations endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02be024f-0b8b-488d-8c3f-2d49ca530dfb"
            }
          ]
        }
      ]
    }
  ]
}