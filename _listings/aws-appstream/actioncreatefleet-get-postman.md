{
  "info": {
    "name": "AWS AppStream 2.0 API Create Fleet",
    "_postman_id": "d79ec233-b1eb-4e4e-b38e-b668dd1601c5",
    "description": "Creates a new fleet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "6d442670-1896-4790-8846-911e09f8455c",
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
              "id": "61757e22-87c6-4a54-bbc9-6ffe0fdaa8dd"
            }
          ]
        },
        {
          "id": "5da5eb94-e9cd-408a-a6ef-2d7e5a05eeac",
          "name": "CreateFleet",
          "request": {
            "url": "http://example.com/api/?Action=CreateFleet?ComputeCapacity=ComputeCapacity&Description=Description&DisconnectTimeoutInSeconds=DisconnectTimeoutInSeconds&DisplayName=DisplayName&ImageName=ImageName&InstanceType=InstanceType&MaxUserDurationInSeconds=MaxUserDurationInSeconds&Name=Name&VpcConfig=VpcConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00a29780-5a62-47cd-b837-12d4377a23a6"
            }
          ]
        }
      ]
    }
  ]
}