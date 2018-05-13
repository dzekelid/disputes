{
  "info": {
    "name": "Stripe Get Disputes Dispute",
    "_postman_id": "b94acdac-638a-4e73-8164-7d21173bb6c6",
    "description": "Retrieves the dispute with the given ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "disputes",
      "item": [
        {
          "id": "3a01bd33-46fe-43db-abb6-e92d6f991241",
          "name": "getDisputesDispute",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "disputes/:dispute"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "dispute",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the dispute with the given ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "950d9481-0ec3-46d0-a3f1-3eec8991a580"
            }
          ]
        }
      ]
    }
  ]
}