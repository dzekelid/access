{
  "info": {
    "name": "AWS Service Catalog API List Portfolio Access",
    "_postman_id": "3772113d-976b-4961-ab64-26f9da96b5fb",
    "description": "Lists the account IDs that have been authorized sharing of the specified\n         portfolio.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "7350caba-b44a-4633-a77a-2a22bc045d95",
          "name": "acceptPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=AcceptPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6233cf79-b633-4a2c-b1a0-7aae4c47c24f"
            }
          ]
        },
        {
          "id": "b526a7e6-8b87-4626-aee8-5642e5fae7b4",
          "name": "associatePrincipalWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociatePrincipalWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN&PrincipalType=PrincipalType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates the specified principal ARN with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "393d8a54-2371-4315-8ce5-30b6aa09542f"
            }
          ]
        },
        {
          "id": "c5b1472d-3567-4a76-baba-751b2b9d1f45",
          "name": "associateProductWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociateProductWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId&SourcePortfolioId=SourcePortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a product with a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "000c6c25-b948-466a-b0d9-e8cd036132fb"
            }
          ]
        },
        {
          "id": "fcfd8f01-bd4a-46cd-b1c7-453c7cbb053b",
          "name": "createPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolio?AcceptLanguage=AcceptLanguage&Description=Description&DisplayName=DisplayName&IdempotencyToken=IdempotencyToken&ProviderName=ProviderName&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ca20db6-369f-478c-a713-58844f4a821d"
            }
          ]
        },
        {
          "id": "08fbffdb-18a5-4987-b13e-53634cca9fd8",
          "name": "createPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3803e11-6085-48b8-9c10-c79b88d94def"
            }
          ]
        },
        {
          "id": "84d44d75-0a75-486b-8542-49a653ead415",
          "name": "deletePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8899bbee-a3c7-4602-9f87-f82274ccaa8b"
            }
          ]
        },
        {
          "id": "1d9fd201-d281-4770-85e9-6cc3e73038cf",
          "name": "deletePortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5c6cfb1-eff2-4b4e-9f1b-e0aa0d30d417"
            }
          ]
        },
        {
          "id": "48417c3d-d10f-4993-b16f-1d558ffcce67",
          "name": "describePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DescribePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information and any tags associated with the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0ee6b81-d5a3-4476-bff5-e4eddcf32de5"
            }
          ]
        },
        {
          "id": "3683b8b1-e39f-4833-a8d4-87a3fd3d3e19",
          "name": "disassociatePrincipalFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociatePrincipalFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a previously associated principal ARN from a specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2638a32e-ba03-4b58-b308-d073f50da075"
            }
          ]
        },
        {
          "id": "1cc01951-4050-4813-a1b7-2d06211248c5",
          "name": "disassociateProductFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateProductFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates the specified product from the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3af64c90-1daa-4cc8-b19e-21cf5cde3d11"
            }
          ]
        },
        {
          "id": "53e27681-175d-4efc-aabb-46a2ad4d5978",
          "name": "listAcceptedPortfolioShares",
          "request": {
            "url": "http://example.com/api/?Action=ListAcceptedPortfolioShares?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists details of all portfolios for which sharing was accepted by this\n         account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a595909-93b6-4196-83f7-39ab4577e69d"
            }
          ]
        },
        {
          "id": "26370dd2-028a-425c-8e59-dcda0ba89294",
          "name": "listConstraintsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListConstraintsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed constraint information for the specified portfolio and\n         product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b18898de-a995-41d2-817e-9d740590e19e"
            }
          ]
        },
        {
          "id": "6e2d85fb-7d79-4b81-a3ac-7282f0780175",
          "name": "listPortfolioAccess",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolioAccess?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account IDs that have been authorized sharing of the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db3bde6c-1704-439d-9df9-5e0b14bc1d09"
            }
          ]
        }
      ]
    },
    {
      "name": "Constraints",
      "item": [
        {
          "id": "60808c66-5a9b-49e9-953d-0e736ec3c6d3",
          "name": "createConstraint",
          "request": {
            "url": "http://example.com/api/?Action=CreateConstraint?AcceptLanguage=AcceptLanguage&Description=Description&IdempotencyToken=IdempotencyToken&Parameters=Parameters&PortfolioId=PortfolioId&ProductId=ProductId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75c35d4b-4b29-43c9-b05f-625a8c118ce7"
            }
          ]
        },
        {
          "id": "acd876cd-6e66-4dd9-906b-1e00f26aadf8",
          "name": "deleteConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31449303-96ea-4902-89f2-dc3662dddea8"
            }
          ]
        },
        {
          "id": "64da7bdd-4b9b-45ae-9a8f-45e65b09b92a",
          "name": "describeConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information for a specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac677f94-19f0-4924-b683-ead14645d093"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "c39635c7-f7b5-4d68-879f-39d968a6caf2",
          "name": "createProduct",
          "request": {
            "url": "http://example.com/api/?Action=CreateProduct?AcceptLanguage=AcceptLanguage&Description=Description&Distributor=Distributor&IdempotencyToken=IdempotencyToken&Name=Name&Owner=Owner&ProductType=ProductType&ProvisioningArtifactParameters=ProvisioningArtifactParameters&SupportDescription=SupportDescription&SupportEmail=SupportEmail&SupportUrl=SupportUrl&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb2736f7-7f72-4870-87f9-9cd9580185dd"
            }
          ]
        },
        {
          "id": "defa6b53-fe40-4732-acc1-2c420772e545",
          "name": "deleteProduct",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "633cb496-0467-46c5-8a78-9112df6c7c38"
            }
          ]
        },
        {
          "id": "3169ea05-db92-4967-9ba0-b1711b0398bb",
          "name": "describeProduct",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27ce080b-eac3-44f4-8f0c-8c8bd40472b4"
            }
          ]
        },
        {
          "id": "78bf6229-8d72-4d8d-9b1f-7a67a9c058de",
          "name": "describeProductAsAdmin",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductAsAdmin?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product, run with administrator\n         access."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ca256cd-5eaf-409e-a2e2-652729c61ee6"
            }
          ]
        },
        {
          "id": "cd76ef27-cd91-4941-b82c-9b02c3f1e11d",
          "name": "describeProductView",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductView?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abce7608-a569-4f35-ab70-fb9c3e58e5aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Artifacts",
      "item": [
        {
          "id": "2e76d148-df46-4426-9f4e-0255d917feee",
          "name": "createProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=CreateProvisioningArtifact?AcceptLanguage=AcceptLanguage&IdempotencyToken=IdempotencyToken&Parameters=Parameters&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new provisioning artifact for the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6ab8ae6-20d6-4163-8ef3-4511e2d9e5aa"
            }
          ]
        },
        {
          "id": "a264576c-5de8-487c-878a-de1c3f1840de",
          "name": "deleteProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b7cad11-fab2-4222-8f59-2154d7e99d59"
            }
          ]
        },
        {
          "id": "27ac4d40-5d26-4ec1-b2c4-22616c28f1bc",
          "name": "describeProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information about the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8382181e-5f8e-4fc8-853f-6e82216817d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Parameters",
      "item": [
        {
          "id": "4adaa131-a5d5-462d-86f8-05d9e6178a91",
          "name": "describeProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningParameters?AcceptLanguage=AcceptLanguage&PathId=PathId&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about parameters required to provision a specified product in a\n         specified manner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "645e2db7-8057-4ab0-9577-6aca0c5257cf"
            }
          ]
        }
      ]
    },
    {
      "name": "Records",
      "item": [
        {
          "id": "0a0baf3d-fd78-4bb9-b5b8-53666baf129d",
          "name": "describeRecord",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRecord?AcceptLanguage=AcceptLanguage&Id=Id&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a paginated list of the full details of a specific request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b77a23a-495a-42e7-99b3-46e93d0c44ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch Paths",
      "item": [
        {
          "id": "d2f39322-49a3-4203-adad-03f6d03b2674",
          "name": "listLaunchPaths",
          "request": {
            "url": "http://example.com/api/?Action=ListLaunchPaths?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all paths to a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24da4edb-530b-4d11-9b07-96a61a37e702"
            }
          ]
        }
      ]
    }
  ]
}