{
  "info": {
    "name": "NPR Get a list of recommendations from a category of content from an organization",
    "_postman_id": "53f5eddd-2ea3-4e2f-8517-110b27450748",
    "description": "This endpoint provides a list of recommendations from a category of content from  an organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "listening",
      "item": [
        {
          "id": "a044bf86-43af-4592-87c9-3142ab29789f",
          "name": "getOrganizationCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.npr.org",
              "path": [
                "listening/v2/organizations/:orgId/categories/:category/recommendations"
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
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "This endpoint provides a list of recommendations from a category of content from  an organization"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbe5b648-7cff-4f0c-b0a7-ad58fd253dfc"
            }
          ]
        }
      ]
    }
  ]
}