{
  "info": {
    "name": "AWS AppStream 2.0 API Delete Fleet",
    "_postman_id": "a72e77a3-1bd2-4aa7-ae68-5d5ceca9a807",
    "description": "Deletes a fleet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "c59ea431-e341-4fa8-8f0e-e91a0ed0d927",
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
              "id": "072fe45b-6903-4dc0-9fb1-72b6b04624c0"
            }
          ]
        },
        {
          "id": "63849fe7-9ba5-45dc-a9f5-c4830deca9a2",
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
              "id": "3d63d774-2404-44a2-9ff1-30b0ae18f824"
            }
          ]
        },
        {
          "id": "f02874ec-1b3b-47da-ba8a-f33518256c76",
          "name": "CreateStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?Description=Description&DisplayName=DisplayName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b0a5965-39be-4168-83ea-7c93a6acb75a"
            }
          ]
        },
        {
          "id": "5207b838-9a0c-4aeb-ab41-f5325b78e0b6",
          "name": "DeleteFleet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFleet?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cc2ee68-b4f8-4387-8442-5defb7269821"
            }
          ]
        }
      ]
    },
    {
      "name": "URL",
      "item": [
        {
          "id": "2f9cb20e-e959-4880-af4a-ad42f5778c25",
          "name": "CreateStreamingURL",
          "request": {
            "url": "http://example.com/api/?Action=CreateStreamingURL?ApplicationId=ApplicationId&FleetName=FleetName&SessionContext=SessionContext&StackName=StackName&UserId=UserId&Validity=Validity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a URL to start an AppStream 2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8512f9e6-6bfb-461a-9ece-d7bc79fe0ca2"
            }
          ]
        }
      ]
    }
  ]
}