{
  "info": {
    "name": "AWS AppStream 2.0 API Update Fleet",
    "_postman_id": "df7e4107-b2ba-4296-a4bf-3d8d19f41c9a",
    "description": "Updates an existing fleet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "27f44f87-cd05-49f6-9df1-b82a4429f048",
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
              "id": "f08e07dd-7be6-491a-91fe-ccaa97c010ac"
            }
          ]
        },
        {
          "id": "22c95e46-1f6a-405a-9590-01b1435128c7",
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
              "id": "c1136fc2-8322-47d5-ab0f-86205248f260"
            }
          ]
        },
        {
          "id": "aff204c2-19ca-454a-ad5e-902e926e3b44",
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
              "id": "13843d17-c38e-4d02-86a1-dd98f8bff14f"
            }
          ]
        },
        {
          "id": "0700535e-9ccb-45f0-a652-08696001781f",
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
              "id": "7c919613-fcb5-4033-8d7c-c78b0080a3e5"
            }
          ]
        },
        {
          "id": "e170e330-f56d-46f7-9593-ffca56a6f2ca",
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
              "id": "5426757c-bbf1-41ce-8385-a766b840cf02"
            }
          ]
        },
        {
          "id": "f157905e-3486-45f9-acd8-032424c0aa3c",
          "name": "DisassociateFleet",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateFleet?FleetName=FleetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a fleet from a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c02588e8-7c2e-44c3-aa27-7a733a62b009"
            }
          ]
        },
        {
          "id": "28f49f29-de49-46a2-acd0-893f879cc204",
          "name": "ListAssociatedFleets",
          "request": {
            "url": "http://example.com/api/?Action=ListAssociatedFleets?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all fleets associated with the stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d64797d5-2bd9-475d-a99d-66f772006524"
            }
          ]
        },
        {
          "id": "c6711fae-cd0c-4c11-a19e-90d76e35db42",
          "name": "StartFleet",
          "request": {
            "url": "http://example.com/api/?Action=StartFleet?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4c1d4f1-cecd-4dcf-8289-625f4077ff13"
            }
          ]
        },
        {
          "id": "7650341c-b248-46f0-b840-037e2f9eb224",
          "name": "StopFleet",
          "request": {
            "url": "http://example.com/api/?Action=StopFleet?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3f6bed5-5b1a-4d83-a20e-b14d65691a70"
            }
          ]
        },
        {
          "id": "ba92f72e-3551-4db9-8077-cb6b5d6be2f9",
          "name": "UpdateFleet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateFleet?ComputeCapacity=ComputeCapacity&DeleteVpcConfig=DeleteVpcConfig&Description=Description&DisconnectTimeoutInSeconds=DisconnectTimeoutInSeconds&DisplayName=DisplayName&ImageName=ImageName&InstanceType=InstanceType&MaxUserDurationInSeconds=MaxUserDurationInSeconds&Name=Name&VpcConfig=VpcConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates an existing fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f82f800-ff34-4376-b4cb-e47dc61410da"
            }
          ]
        }
      ]
    },
    {
      "name": "URL",
      "item": [
        {
          "id": "0e318533-949e-481c-a0b5-0bbe53f15575",
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
              "id": "a1320532-13a3-4d02-b2fd-492e7ac3b0cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack",
      "item": [
        {
          "id": "3d28eb1a-7c34-4bd9-8e41-d334eeea432b",
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
              "id": "570a134f-9ae3-471a-8e7e-0072331342aa"
            }
          ]
        },
        {
          "id": "9079dc72-9aba-41e8-82ac-d045f9327f85",
          "name": "ListAssociatedStacks",
          "request": {
            "url": "http://example.com/api/?Action=ListAssociatedStacks?FleetName=FleetName&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all stacks to which the specified fleet is associated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e80cbea-dfee-42b8-ae26-ef5ce4621d2f"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "4860f425-75a1-4c37-9ebd-27537ee7ed33",
          "name": "DescribeImages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Names=Names",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the images."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "693f72e6-5a82-4fca-8ce4-63e9ba4f5ffa"
            }
          ]
        }
      ]
    },
    {
      "name": "Sessions",
      "item": [
        {
          "id": "bd3215eb-44d6-4ff9-93b4-c54aae8ebbaf",
          "name": "DescribeSessions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSessions?FleetName=FleetName&Limit=Limit&NextToken=NextToken&StackName=StackName&UserId=UserId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the streaming sessions for a stack and a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0565a7f4-c902-49dc-b67f-e3ac0d4ecf3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "dafac47e-efa7-4dcc-a0aa-9baac5724c7b",
          "name": "DescribeStacks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStacks?Names=Names&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If stack names are not provided, this operation describes the specified stacks;\n            otherwise, all stacks in the account are described."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c3a4811-6852-4805-9a6a-a596ae85943b"
            }
          ]
        }
      ]
    },
    {
      "name": "Session",
      "item": [
        {
          "id": "64d084d0-1430-4805-8f90-79a1b667988a",
          "name": "ExpireSession",
          "request": {
            "url": "http://example.com/api/?Action=ExpireSession?SessionId=SessionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This operation immediately stops a streaming session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84eb5681-d055-4d2a-a7c9-d0eefd905847"
            }
          ]
        }
      ]
    }
  ]
}