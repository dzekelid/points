{
  "info": {
    "name": "Attom Data Solutions API Returns all boundaries a point falls within.",
    "_postman_id": "c6283b26-ecd3-40bf-91ec-55bd7ec8b977",
    "description": "This method allows you to pass a latitude and longitude point and geo type to retrieve a list of geographies that point falls within. Required input is a valid WKT (Well Known Text) point.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "6c1015ec-33b8-494b-b6c7-1ec19a48cdb4",
          "name": "getPropertyIdList",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/id?geoid=%7B%7D&maxBeds=%7B%7D&minBeds=%7B%7D&orderby=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of property IDs within a specific geography that have a specific number of beds. Use orderby to choose how you want your results sorted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c6f9c95-ee19-4004-8447-ff94ebcf0b11"
            }
          ]
        },
        {
          "id": "c6faf44c-9e7d-4c82-833a-56a6a0efc8bd",
          "name": "propertyDetails",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/detail?address=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get property details based on its Onboard property ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0945ee5e-cff9-4be3-88d8-5b596018e7f7"
            }
          ]
        },
        {
          "id": "b1cf2ace-de93-46b7-820b-de4b0324ba02",
          "name": "adressList",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/address?address1=%7B%7D&address2=%7B%7D&orderby=%7B%7D&page=%7B%7D&pagesize=%7B%7D&postalcode=%7B%7D&propertytype=%7B%7D&radius=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of properties within a zip code. Use propertytype and order by to narrow down your results."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e06a02ab-148a-4ac4-b4f2-94e47563b9d4"
            }
          ]
        },
        {
          "id": "67d44bb5-9413-4ae3-bf95-4b11f2c68e79",
          "name": "propertySnapshot",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/snapshot?cityname=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&maxavmvalue=%7B%7D&maxLotSize1=%7B%7D&maxtaxamt=%7B%7D&minavmvalue=%7B%7D&minLotSize1=%7B%7D&mintaxamt=%7B%7D&orderby=%7B%7D&postalcode=%7B%7D&propertytype=%7B%7D&radius=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of property snapshots within a specific city that are within a desired size range and a specific property type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8c826c6-95c9-4c69-a86c-b279db184aad"
            }
          ]
        },
        {
          "id": "f3a1ab43-a2c7-466c-b86b-7eefa179fac0",
          "name": "propertyBasicProfile",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/basicprofile?attomid=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get basic property information and most recent transaction and taxes for a specific attom id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7835ef8-a298-4827-a11c-5d0c5b75fe13"
            }
          ]
        },
        {
          "id": "a2862243-5645-4a18-976a-f4ecdcbcd855",
          "name": "propertyExpandedProfile",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/expandedprofile?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a detailed property information and most recent transaction and taxes for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ee416e3-d619-497c-ab5a-aa0cf0af4c4e"
            }
          ]
        },
        {
          "id": "e7ad7185-7747-430d-8bde-9b9cbc3feb16",
          "name": "getAllEventsDetailAddress",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/allevents/detail?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "API Security Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a detail of all the events on a specific property based on its address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11c2d42e-1c4a-40c9-9b3c-c897ec29bb93"
            }
          ]
        },
        {
          "id": "8624b4ca-95c3-4af4-ac40-90ad783bd392",
          "name": "propertyDetailsMortage",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/detailmortgage?address1=%7B%7D&address2=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get property details mortgage based on its Onboard property ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9a0ac6a-adc8-43a6-844f-9bbfbea8143a"
            }
          ]
        },
        {
          "id": "5d262181-e1dc-4b38-b183-63f9962d0728",
          "name": "propertyDetailsOwner",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/detailowner?address1=%7B%7D&address2=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get property details owner based on its Onboard property ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30d446a8-e50e-4671-b8a3-9a0b603cf510"
            }
          ]
        },
        {
          "id": "543d597b-c1f6-4fe6-8c41-c6785e6919ee",
          "name": "propertyDetailsMortgageOwner",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/detailmortgageowner?address1=%7B%7D&address2=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get property details mortgageowner based on its Onboard property ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd5a4b84-df0a-4c8c-8171-a210877a400e"
            }
          ]
        },
        {
          "id": "09d97426-180c-4650-b6c1-d45c17d40f8a",
          "name": "getAssessmentSnapshotTotal",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/assessment/snapshot?address1=%7B%7D&address2=%7B%7D&maxmktttlvalue=%7B%7D&minmktttlvalue=%7B%7D&radius=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get snapshots of the properties within a radius of a property that have a total market value within a specified range."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25cfe183-616b-4282-ae6a-369d29633004"
            }
          ]
        },
        {
          "id": "01eb3d63-4101-4ecc-9175-180651f07f7b",
          "name": "assessmenDetailPropertyId",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/assessment/detail?postalcode=%7B%7D&propertytype=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get assessment details for properties within a zip code. Use propertytpe to select a specific property type for your search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb6dabef-0334-4c78-b441-b0d9e47697aa"
            }
          ]
        },
        {
          "id": "b2ab260b-93da-4d5f-8bef-f6653e69227e",
          "name": "assessmentHistoryDetailID",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/assessmenthistory/detail?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a full detail of property characteristics and assessment history information for a specific property."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50e8d3da-3af3-4485-a181-7a4cc59f3e1c"
            }
          ]
        },
        {
          "id": "e1f718c8-801a-43d6-8c61-7c67cc57eb8c",
          "name": "avmSnapshotGeoID",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/avm/snapshot?geoid=%7B%7D&maxavmvalue=%7B%7D&minavmvalue=%7B%7D&propertytype=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of AVM snapshot records that fall within an Onboard GeoID with a specific value range. Use propertytpe to select a specific property type for your search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6c30fa1-c209-4ce7-b0e4-abf9ff53b48a"
            }
          ]
        },
        {
          "id": "99b9fbd5-d00b-4657-8582-0ebd32f4172b",
          "name": "avmDetailPostal",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/avm/detail?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get AVM details for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45337123-c5ec-4914-b1a9-ed2a733bbc7c"
            }
          ]
        },
        {
          "id": "638137cf-4707-4909-b33f-0cb97cd79af9",
          "name": "attomAvmDetail",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/attomavm/detail?attomid=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get Attomized AVM and other property details for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8bb33321-7ae9-4549-8e70-ae9bd42cd914"
            }
          ]
        },
        {
          "id": "1dc5b3e3-c975-4dd0-85e3-7a06639e68ce",
          "name": "getHomeSaleSnapshotsGeoId",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/sale/snapshot?address1=%7B%7D&address2=%7B%7D&endsalesearchdate=%7B%7D&geoid=%7B%7D&maxsaleamt=%7B%7D&minsaleamt=%7B%7D&propertytype=%7B%7D&radius=%7B%7D&startsalesearchdate=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of home sale snapshots within a Onboard GeoID that sold within a date range and specified sale amount."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "534dcd69-ea6e-49ad-b9c8-768da3311930"
            }
          ]
        },
        {
          "id": "ce4bf2bb-8e82-4e96-a925-a56dab3c392c",
          "name": "getSaleDetailPostal",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/sale/detail?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get sales information for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc7481cb-e641-4103-81d2-5a3c458d2011"
            }
          ]
        },
        {
          "id": "b8fe79c7-f33f-42a8-bc81-310394919b61",
          "name": "getSaleHistorySnapshotPropertyId",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/saleshistory/snapshot?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a sales history snapshot of a property based on an Onboard property ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cac324c4-fcac-4a30-bd69-55c82f9b8ce6"
            }
          ]
        },
        {
          "id": "1db96ecb-e2c9-4aa6-8ccf-a287d1c58af4",
          "name": "saleHistoryBasicHistory",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/saleshistory/basichistory?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the basic transaction and loan history on a property for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2dc2133-6225-4de8-b7cf-274daead754d"
            }
          ]
        },
        {
          "id": "830f1c76-fd2b-4a24-968f-e77e9aa40ac0",
          "name": "saleHistoryExpandedHistory",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/saleshistory/expandedhistory?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the detailed transaction, pre-foreclosure and loan history on a property for a specific address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5886dc34-f509-47dd-b9ba-15a24562dcb0"
            }
          ]
        },
        {
          "id": "e740db3a-0eb6-40c9-9b94-9a07f5db774e",
          "name": "getSaleHistoryDetailAddress",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/saleshistory/detail?address1=%7B%7D&address2=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a sales history snapshot of a property based on an address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d67288db-80e2-446e-a1d8-29f2fa652995"
            }
          ]
        },
        {
          "id": "8235b9ac-aa99-4e54-a962-8c08a84368fc",
          "name": "getSalesTrendByYear",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/salestrend/snapshot?endmonth=%7B%7D&endyear=%7B%7D&geoid=%7B%7D&interval=%7B%7D&startmonth=%7B%7D&startyear=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the average sale price, median sale price, and count of sales for the past 2 years in yearly intervals."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "186378ca-2844-4c6a-9d05-2806bae1e83d"
            }
          ]
        },
        {
          "id": "79ddc724-78fe-4364-a92a-c04bc30be7a9",
          "name": "getAreaHierarchyLookup",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/hierarchy/lookup?geoType=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&WKTString=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This method allows you to pass a latitude and longitude point and geo type to retrieve a list of geographies that point falls within. Required input is a valid WKT (Well Known Text) point."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0bf0e1d5-0fad-4958-aff2-178821a376c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Return",
      "item": [
        {
          "id": "70c238c8-08f2-4b72-859f-15bef991dd45",
          "name": "propertyDetailsWithSchools",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/property/detailwithschools?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for a property to have the property details returned, along with the schools in the associated attendance zones."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f46dba3-d5fc-459e-b556-5cc6a4379ae0"
            }
          ]
        },
        {
          "id": "96085cb5-9bd8-46d6-8e0b-375ef2f7d732",
          "name": "propertySchoolSnapshot",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/school/snapshot?filetypetext=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&radius=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for all schools that are located within a given radius around a given latitude and longitude."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2093d270-6fff-4c6c-a499-adce293ecacd"
            }
          ]
        },
        {
          "id": "f6396d5d-5bcc-4479-8b53-26d32be9a9ab",
          "name": "propertyDetails",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/school/detail?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search by school ID to return all of the available details about a school"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d91253a-ef0c-49b4-bfe7-7d8c9a106fd3"
            }
          ]
        },
        {
          "id": "6880ab15-0708-4ef2-805d-68efb8961960",
          "name": "propertySchoolDistrictDetail",
          "request": {
            "url": "http://search.onboard-apis.com/communityapi/v2.0.0/school/districtdetail?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "accept",
                "value": "{}",
                "description": "application/xml or application/json (default)",
                "disabled": false
              },
              {
                "key": "apikey",
                "value": "{}",
                "description": "Application Key",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search by district number to return all of the available details about a school district"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffcae3eb-db82-4abd-88ca-317d4fea422b"
            }
          ]
        }
      ]
    }
  ]
}