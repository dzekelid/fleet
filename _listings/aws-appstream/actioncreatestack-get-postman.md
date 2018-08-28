{
  "info": {
    "name": "AWS AppStream 2.0 API Create Stack",
    "_postman_id": "a23812cd-464d-4850-8b59-55172116ec92",
    "description": "Create a new stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "56621f16-ad29-4f7b-9ae5-2db1c602dc56",
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
              "id": "a5cde1bc-80f1-4391-9004-08d01eceafb9"
            }
          ]
        },
        {
          "id": "5a299035-655a-4bf3-a198-8b30a14c0e4b",
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
              "id": "da69cce6-da3c-49a2-a7f5-f0c7c0de4b28"
            }
          ]
        },
        {
          "id": "9c8e1e18-e787-4108-a27f-86ed22ac8d58",
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
              "id": "7500ccb0-46c3-40f2-99bf-ec0f9f190590"
            }
          ]
        }
      ]
    }
  ]
}