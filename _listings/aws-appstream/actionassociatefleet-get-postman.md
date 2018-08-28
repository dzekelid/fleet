{
  "info": {
    "name": "AWS AppStream 2.0 API Associate Fleet",
    "_postman_id": "e03b7199-b89b-4696-8e7b-aba790a70098",
    "description": "Associate a fleet to a stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "eab64d03-781d-430a-bcde-ec5d24681444",
          "name": "AssociateFleet",
          "request": {
            "url": "http://example.com/api/?Action=AssociateFleet?FleetName=FleetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associate a fleet to a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6ae87a2-5813-4a5c-9370-c4575da247ba"
            }
          ]
        }
      ]
    }
  ]
}