{
  "info": {
    "name": "AWS CloudSearch Describe Service Access Policies",
    "_postman_id": "a9161d84-f52d-4ab6-864a-75f686a8b5e7",
    "description": "Gets information about the access policies that control access to the domain's document and search endpoints.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "0555d6fa-8fcd-4258-8d94-aadf5210d707",
          "name": "AddTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?Base=Base&InternalException=InternalException&LimitExceededException=LimitExceededException&ValidationException=ValidationException",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches resource tags to an\n Amazon CloudSearch domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fb8f14c-5658-4597-9698-ed766a5bc3a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Suggesters",
      "item": [
        {
          "id": "d320046b-f417-4388-8833-e4b2f07754e6",
          "name": "BuildSuggesters",
          "request": {
            "url": "http://example.com/api/?Action=BuildSuggesters?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Indexes the search suggestions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f2f8a77-ceb0-4034-9889-504722414358"
            }
          ]
        },
        {
          "id": "fdbc9a6f-d244-4410-9306-fa31573ccc89",
          "name": "DefineSuggester",
          "request": {
            "url": "http://example.com/api/?Action=DefineSuggester?DomainName=DomainName&Suggester=Suggester",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures a suggester for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a825485b-86b3-4b58-98a6-88133c599bba"
            }
          ]
        },
        {
          "id": "a06382a6-b743-449c-8189-b6319b633cd8",
          "name": "DeleteSuggester",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSuggester?DomainName=DomainName&SuggesterName=SuggesterName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a suggester."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5f63d58-1c79-4b5d-a02c-0925bcfbea3d"
            }
          ]
        }
      ]
    },
    {
      "name": "Domains",
      "item": [
        {
          "id": "4100fd5c-2c54-438b-902f-406079106bc2",
          "name": "CreateDomain",
          "request": {
            "url": "http://example.com/api/?Action=CreateDomain?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "577925e4-0118-47d0-9475-92593b0a5587"
            }
          ]
        },
        {
          "id": "f25b0a79-c0be-40ea-9f68-4ee0bc87dfc0",
          "name": "DeleteDomain",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDomain?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Permanently deletes a search domain and all of its data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0edccf8e-059e-4187-ad84-21a337248053"
            }
          ]
        },
        {
          "id": "d6a0bb5c-7e95-44c1-bd9f-cba5f1452a66",
          "name": "DescribeDomains",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDomains?DomainNames.member.N=DomainNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the search domains owned by this account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44deeb2a-4c16-4174-973a-f8e22d6cf2d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Analysis Scheme",
      "item": [
        {
          "id": "125c61ef-e9e9-4974-abad-9bb176231216",
          "name": "DefineAnalysisScheme",
          "request": {
            "url": "http://example.com/api/?Action=DefineAnalysisScheme?AnalysisScheme=AnalysisScheme&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an analysis scheme that can be applied to a text or text-array field to define language-specific text processing options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28b05f3c-6a64-413b-8c76-80d02c55a8e0"
            }
          ]
        },
        {
          "id": "1558c0de-8e5f-4751-8f34-96ee858a265b",
          "name": "DeleteAnalysisScheme",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAnalysisScheme?AnalysisSchemeName=AnalysisSchemeName&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an analysis scheme."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05dda054-c74a-45fa-9365-62f7313f518f"
            }
          ]
        },
        {
          "id": "6aef82e5-ba6e-4b5f-bec9-e7ba21e1066c",
          "name": "DescribeAnalysisSchemes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAnalysisSchemes?AnalysisSchemeNames.member.N=AnalysisSchemeNames.member.N&Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the analysis schemes configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80b25d31-95e0-491e-82ee-07bc7bff2307"
            }
          ]
        }
      ]
    },
    {
      "name": "Expressions",
      "item": [
        {
          "id": "e1788a6a-9b85-4730-87e6-03209dcb2b8c",
          "name": "DefineExpression",
          "request": {
            "url": "http://example.com/api/?Action=DefineExpression?DomainName=DomainName&Expression=Expression",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an Expression  for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d61ab85-a0ff-4cff-af3f-bc21bd80d761"
            }
          ]
        },
        {
          "id": "45fcd2f9-3579-4d03-85ff-c7b74f711cd1",
          "name": "DeleteExpression",
          "request": {
            "url": "http://example.com/api/?Action=DeleteExpression?DomainName=DomainName&ExpressionName=ExpressionName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes an \n  Expression\n  from the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c4d1030-dec6-4cbf-a7fa-40797e51cc90"
            }
          ]
        },
        {
          "id": "ba35f96a-bfda-4b51-b51e-7c007db4a424",
          "name": "DescribeExpressions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeExpressions?Deployed=Deployed&DomainName=DomainName&ExpressionNames.member.N=ExpressionNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the expressions configured for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5ac3eb5-1a4c-4601-bbdc-36c4c31f14bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Index Fields",
      "item": [
        {
          "id": "6e244ebb-d6fd-46c8-a7ed-509186360e07",
          "name": "DefineIndexField",
          "request": {
            "url": "http://example.com/api/?Action=DefineIndexField?DomainName=DomainName&IndexField=IndexField",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an ndexField  for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3fe06a28-d9eb-4dba-a67f-365289f34219"
            }
          ]
        },
        {
          "id": "eb7ab452-9e6a-4c9e-932f-f7c582ff47fc",
          "name": "DeleteIndexField",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIndexField?DomainName=DomainName&IndexFieldName=IndexFieldName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes an \n  IndexField\n  from the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0cd721f0-dbeb-4e72-9eef-dee25143caf8"
            }
          ]
        },
        {
          "id": "bd570282-c067-4516-8415-a9e8e1392ae3",
          "name": "DescribeIndexFields",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIndexFields?Deployed=Deployed&DomainName=DomainName&FieldNames.member.N=FieldNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the index fields configured for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d36a036-0084-4f51-a385-df7e514a853f"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Options",
      "item": [
        {
          "id": "b5e7418d-7744-48dc-84d5-d10cc8730b09",
          "name": "DescribeAvailabilityOptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAvailabilityOptions?Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the availability options configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bdf94a30-67b5-4bf4-8f06-020b54cbf403"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Parameters",
      "item": [
        {
          "id": "526442da-c0ca-4e35-be30-412afce3f51c",
          "name": "DescribeScalingParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScalingParameters?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the scaling parameters configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7192906b-5c02-43b2-a0b2-19abfd9119a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Access Policies",
      "item": [
        {
          "id": "97707c64-d024-4d60-adf4-b364ccefacb5",
          "name": "DescribeServiceAccessPolicies",
          "request": {
            "url": "http://example.com/api/?Action=DescribeServiceAccessPolicies?Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the access policies that control access to the domain's document and search endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38371202-aec8-4e07-a8c5-df4958e454e1"
            }
          ]
        }
      ]
    }
  ]
}