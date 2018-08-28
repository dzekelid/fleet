{
  "info": {
    "name": "AWS AppStream 2.0 API Describe Fleets",
    "_postman_id": "6cd97c7a-e158-46ca-b422-ee6b294d0e4f",
    "description": "If fleet names are provided, this operation describes the specified fleets;\n            otherwise, all the fleets in the account are described.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "e3aeafc5-3296-45a6-a772-705f600fb0b8",
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
              "id": "8c5058b7-20a2-4776-b32c-e207bf885e54"
            }
          ]
        },
        {
          "id": "dcf02a13-7901-4911-b1fd-169c3e352794",
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
              "id": "b03d64ac-a6f3-48fd-bda5-7642f6c09ae0"
            }
          ]
        },
        {
          "id": "3fab2293-02f8-429c-be1e-48f0d79e8c3c",
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
              "id": "72ff82e3-8e4b-4264-b229-662d38e661aa"
            }
          ]
        },
        {
          "id": "9875c6af-268b-46a6-a883-7c88dae7e10c",
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
              "id": "dee51232-7b66-432e-a8da-52face94464a"
            }
          ]
        },
        {
          "id": "d06efa48-53af-40d6-b5c6-133743100396",
          "name": "DescribeFleets",
          "request": {
            "url": "http://example.com/api/?Action=DescribeFleets?Names=Names&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If fleet names are provided, this operation describes the specified fleets;\n            otherwise, all the fleets in the account are described."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e5cf702-1bf1-4df6-92db-83989ac1d831"
            }
          ]
        }
      ]
    },
    {
      "name": "URL",
      "item": [
        {
          "id": "d688d944-6d92-4af3-a1e8-12879a10c661",
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
              "id": "5d9858cd-5738-41d9-8620-653912ff6f10"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack",
      "item": [
        {
          "id": "bee51408-3951-4b63-9616-13582af0fb31",
          "name": "DeleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43a6231a-d307-41cd-9d26-42786808fd24"
            }
          ]
        }
      ]
    }
  ]
}