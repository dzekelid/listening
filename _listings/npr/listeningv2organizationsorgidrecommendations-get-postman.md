{
  "info": {
    "name": "NPR Get a variety of details about an organization including various lists of recent audio items",
    "_postman_id": "e4d81cc4-25cc-4e2b-bc7f-44efcae279b6",
    "description": "This endpoint provides a variety of details about an organization including various lists of recent audio items.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "7b98848d-e466-428c-af99-f6a0689cc4fd",
          "name": "getOrganizationOverview",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.npr.org",
              "path": [
                "listening/v2/organizations/:orgId/recommendations"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "orgId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint provides a variety of details about an organization including various lists of recent audio items"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "787d2adf-f200-4e5e-9617-35a643f47cad"
            }
          ]
        }
      ]
    }
  ]
}