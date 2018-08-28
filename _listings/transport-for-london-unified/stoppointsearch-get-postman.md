{
  "info": {
    "name": "Transport for London Unified Stop Point  Search",
    "_postman_id": "c4b69c20-9e82-42ee-a976-60396cf63ab7",
    "description": "Search stoppoints by their common name, or their 5-digit countdown bus stop code..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accent",
      "item": [
        {
          "id": "f62de918-487b-4704-a583-25201672c00b",
          "name": "AccidentStats_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "AccidentStats/:year"
              ],
              "variable": [
                {
                  "id": "year",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all accident details for accidents occuring in the specified year."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbf5d839-ef7d-4063-add0-27d4a77cf53e"
            }
          ]
        }
      ]
    },
    {
      "name": "Air",
      "item": [
        {
          "id": "caff628e-cf6e-44b8-af0b-8aa2405c4b26",
          "name": "AirQuality_Get",
          "request": {
            "url": "http://api.tfl.gov.uk/AirQuality",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets air quality data feed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05c59d7d-80d1-4912-a382-254b9f8b5eec"
            }
          ]
        }
      ]
    },
    {
      "name": "Bike",
      "item": [
        {
          "id": "944148d0-069a-434f-a72d-ad075795cec7",
          "name": "BikePoint_GetAll",
          "request": {
            "url": "http://api.tfl.gov.uk/BikePoint",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all bike point locations. the place object has an addtionalproperties array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks - (nbbikes + nbspa."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e82c864d-839b-493a-bdf3-a6132663ff52"
            }
          ]
        },
        {
          "id": "c8303be2-2dfa-4be5-bd3b-22bbb4b50b5c",
          "name": "BikePoint_Search",
          "request": {
            "url": "http://api.tfl.gov.uk/BikePoint/Search?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for bike stations by their name, a bike point's name often contains information about the name of the street\r\n            or nearby landmarks, for example. note that the search result does not contain the placeproperties i.e. the status\r\n     ."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee84c03b-d396-4642-ba95-5cc89fe39b80"
            }
          ]
        },
        {
          "id": "079be489-bc42-4d51-8d8f-8d01ff9850a4",
          "name": "BikePoint_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "BikePoint/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the bike point with the given id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df9917fa-0a54-4cf5-a760-c46a157a97d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Cabwise",
      "item": [
        {
          "id": "ac65bcb9-0559-4d10-9eb2-da5ed9deed7c",
          "name": "Cabwise_Get",
          "request": {
            "url": "http://api.tfl.gov.uk/Cabwise/search?forceXml=%7B%7D&lat=%7B%7D&legacyFormat=%7B%7D&lon=%7B%7D&maxResults=%7B%7D&name=%7B%7D&optype=%7B%7D&radius=%7B%7D&twentyFourSevenOnly=%7B%7D&wc=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets taxis and minicabs contact information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db85bd3a-2337-4136-8bd9-bb51bf6055b7"
            }
          ]
        }
      ]
    },
    {
      "name": "Journey",
      "item": [
        {
          "id": "63b4d530-232d-4d48-96dd-87d923492dd2",
          "name": "Journey_JourneyResults",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Journey/JourneyResults/:from/to/:to"
              ],
              "query": [
                {
                  "key": "accessibilityPreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "adjustment",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "alternativeCycle",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "alternativeWalking",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "applyHtmlMarkup",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "bikeProficiency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "cyclePreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fromName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "journeyPreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxTransferMinutes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxWalkingMinutes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "nationalSearch",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "taxiOnlyTrip",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "time",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "timeIs",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "useMultiModalCall",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "via",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "viaName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "walkingOptimization",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "walkingSpeed",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "from",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "to",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Perform a journey planner search from the parameters specified in simple types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abc72b84-5d65-437c-9604-1621fd42becf"
            }
          ]
        },
        {
          "id": "e51e5448-aa2f-4e1a-9ee8-b37b6330355a",
          "name": "Journey_Meta",
          "request": {
            "url": "http://api.tfl.gov.uk/Journey/Meta/Modes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the available journey planner modes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8548496d-e681-404b-a041-34b837551bd0"
            }
          ]
        }
      ]
    },
    {
      "name": "Line",
      "item": [
        {
          "id": "971c1c8c-4541-441e-b46e-574dd9954024",
          "name": "Line_MetaDisruptionCategories",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/DisruptionCategories",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid disruption categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15dd8f2f-fc4d-42ca-a347-3fb90c8dadc3"
            }
          ]
        },
        {
          "id": "cfef76b1-fe7f-46d5-9d85-53858ca9fb83",
          "name": "Line_MetaModes",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/Modes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid modes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "adfb7aba-f32b-4ccd-ac79-e813cbefd259"
            }
          ]
        },
        {
          "id": "e21be379-43d0-4de0-9516-a291f40932e2",
          "name": "Line_MetaServiceTypes",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/ServiceTypes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid servicetypes to filter on."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4162dc3e-8423-4243-98d0-6aaf649d8fac"
            }
          ]
        },
        {
          "id": "51114adf-1c31-4a88-933f-37cf19d14e40",
          "name": "Line_MetaSeverity",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/Severity",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid severity codes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcd89194-0301-4de0-a672-4141b07a0eb7"
            }
          ]
        },
        {
          "id": "33d9ef50-0412-49eb-a589-14db89df1030",
          "name": "Line_GetByMode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Mode/:modes"
              ],
              "variable": [
                {
                  "id": "modes",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets lines that serve the given modes.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bf480e2-4ee9-46ad-8293-982768273163"
            }
          ]
        },
        {
          "id": "760c29c6-8a4f-4b42-b4af-0c970005326d",
          "name": "Line_DisruptionByMode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Mode/:modes/Disruption"
              ],
              "variable": [
                {
                  "id": "modes",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get disruptions for all lines of the given modes.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3554ec13-d261-4e9b-8cf6-ab99636b9d14"
            }
          ]
        },
        {
          "id": "74d58932-222d-43b0-b6ec-f2f513316b2e",
          "name": "Line_RouteByMode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Mode/:modes/Route"
              ],
              "query": [
                {
                  "key": "serviceTypes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "modes",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all lines and their valid routes for given modes, including the name and id of the originating and terminating stops for each route."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a5690e9-0968-41fb-905b-c1bfd2803c47"
            }
          ]
        },
        {
          "id": "44879dc4-13b6-4e6f-8796-817627362bfb",
          "name": "Line_StatusByMode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Mode/:modes/Status"
              ],
              "query": [
                {
                  "key": "detail",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "modes",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the line status of for all lines for the given modes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af49a275-6f04-4ae6-9fa7-f2622e30da24"
            }
          ]
        },
        {
          "id": "85a9a616-faf9-49b7-82ea-57c03f1e943b",
          "name": "Line_Route",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Route?serviceTypes=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get all valid routes for all lines, including the name and id of the originating and terminating stops for each route.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "737a340a-8ebe-4ff2-8c28-4af432c55135"
            }
          ]
        },
        {
          "id": "c5f04e87-b8ab-4d13-a937-6168199bec9c",
          "name": "Line_Search",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Search/:query"
              ],
              "query": [
                {
                  "key": "modes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "serviceTypes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "query",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for lines or routes matching the query string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96ba28f9-8230-4982-b681-4366871ec526"
            }
          ]
        },
        {
          "id": "6663a3fa-fe9e-454d-a2e7-606f464f6282",
          "name": "Line_StatusBySeverity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/Status/:severity"
              ],
              "variable": [
                {
                  "id": "severity",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the line status for all lines with a given severity\r\n            a list of valid severity codes can be obtained from a call to line/meta/severity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d8b30e8-5253-4ed7-881e-cb40c436100e"
            }
          ]
        },
        {
          "id": "e73fe6de-3532-4181-8288-ff9cfc61966f",
          "name": "Line_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets lines that match the specified line ids.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8fecc18-2089-41de-bb47-88fc93c91fba"
            }
          ]
        },
        {
          "id": "80cd0e05-c556-4070-84f4-fd7ba5da1b77",
          "name": "Line_Arrivals",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids/Arrivals/:stopPointId"
              ],
              "query": [
                {
                  "key": "destinationStationId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "direction",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "stopPointId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the list of arrival predictions for given line ids based at the given stop."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35c48c6b-6523-4e59-8dab-c179a397db2b"
            }
          ]
        },
        {
          "id": "b82b7b7d-364d-479a-b261-06dd9a9a1383",
          "name": "Line_Disruption",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids/Disruption"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get disruptions for the given line ids."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "104c0759-5263-45d6-8c68-c833a5048828"
            }
          ]
        },
        {
          "id": "fc348918-f1aa-471f-9628-e671f1835046",
          "name": "Line_LineRoutesByIds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids/Route"
              ],
              "query": [
                {
                  "key": "serviceTypes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get all valid routes for given line ids, including the name and id of the originating and terminating stops for each route.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c86a019-d47b-4633-b437-d40f89424e45"
            }
          ]
        },
        {
          "id": "daecb52e-4699-49db-8e74-168e35e4c975",
          "name": "Line_StatusByIds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids/Status"
              ],
              "query": [
                {
                  "key": "detail",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the line status of for given line ids e.g minor delays."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a708fb4-9e6a-4892-98c0-a84ddc209f21"
            }
          ]
        },
        {
          "id": "fba5b7f6-0e3c-49a2-8ca0-9d0487da69f6",
          "name": "Line_Status",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:ids/Status/:StartDate/to/:EndDate"
              ],
              "query": [
                {
                  "key": "dateRange.endDate",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "dateRange.startDate",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "detail",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "EndDate",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "StartDate",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "endDate",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "startDate",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the line status for given line ids during the provided dates e.g minor delays."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1bc57c0-56c4-4ef8-9afd-27b2a6b53517"
            }
          ]
        },
        {
          "id": "2943da16-4e0c-4731-be0e-e27697efb4c8",
          "name": "Line_RouteSequence",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:id/Route/Sequence/:direction"
              ],
              "query": [
                {
                  "key": "excludeCrowding",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "serviceTypes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "direction",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all valid routes for given line id, including the sequence of stops on each route.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "692135cd-2d03-47c8-a6a5-2264563ca0be"
            }
          ]
        },
        {
          "id": "be49b02e-af15-4628-ba4a-443a747fae45",
          "name": "Line_StopPoints",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:id/StopPoints"
              ],
              "query": [
                {
                  "key": "tflOperatedNationalRailStationsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of the stations that serve the given line id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03d87414-8dfd-4f00-81ba-c17ef66658d4"
            }
          ]
        },
        {
          "id": "eb896755-8dcf-4840-8497-cc1be279ff6c",
          "name": "Line_Timetable",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:id/Timetable/:fromStopPointId"
              ],
              "variable": [
                {
                  "id": "fromStopPointId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the timetable for a specified station on the give line."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ba62dd1-d169-46d3-969c-10650537e358"
            }
          ]
        },
        {
          "id": "39803eef-10d5-45cb-a8a9-97e119d4f20e",
          "name": "Line_TimetableTo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Line/:id/Timetable/:fromStopPointId/to/:toStopPointId"
              ],
              "variable": [
                {
                  "id": "fromStopPointId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "toStopPointId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the timetable for a specified station on the give line with specified destination."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3950a734-c97c-4efb-a7cb-3444d95531d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Mode",
      "item": [
        {
          "id": "66d52daf-1f32-4bb3-9cfb-20202338c0fe",
          "name": "Mode_GetActiveServiceTypes",
          "request": {
            "url": "http://api.tfl.gov.uk/Mode/ActiveServiceTypes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the service type active for a mode.\r\n            currently only supports tube."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bd6cc24-f404-4c2a-964b-fa8361ddcbdf"
            }
          ]
        },
        {
          "id": "179c42ca-6ead-402f-a4c1-9558faefba76",
          "name": "Mode_Arrivals",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Mode/:mode/Arrivals"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "mode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the next arrival predictions for all stops of a given mode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e54d3c1-4d26-4d85-8e16-3ee921740da0"
            }
          ]
        }
      ]
    },
    {
      "name": "Occupancy",
      "item": [
        {
          "id": "cf19e438-b6e3-4388-b57a-cb704580981a",
          "name": "Occupancy_GetBikePointsOccupancies",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Occupancy/BikePoints/:ids"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the occupancy for bike points.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d17abec-c71b-4f7e-9964-0e0795c9f772"
            }
          ]
        },
        {
          "id": "c5a932ea-f320-43af-b9ef-94707dcc44b4",
          "name": "Occupancy.CarPark.get",
          "request": {
            "url": "http://api.tfl.gov.uk/Occupancy/CarPark",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the occupancy for all car parks that have occupancy data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5216224-8be1-4f16-ae54-f3661c6a6f8f"
            }
          ]
        },
        {
          "id": "58d8e31c-2a9b-43ff-8c93-5b05e4553662",
          "name": "Occupancy.CarPark.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Occupancy/CarPark/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the occupancy for a car park with a given id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1528d4e-96ff-428a-b1e6-92598baa38c4"
            }
          ]
        },
        {
          "id": "889cc51f-d608-4012-8967-be86fbecb878",
          "name": "Occupancy_GetAllChargeConnectorStatus",
          "request": {
            "url": "http://api.tfl.gov.uk/Occupancy/ChargeConnector",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the occupancy for all charge connectors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f62153a6-0e24-433d-a904-7ca2620d6871"
            }
          ]
        },
        {
          "id": "b8dc4bf6-9b5b-449b-a3cc-8b9b3d17645c",
          "name": "Occupancy_GetChargeConnectorStatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Occupancy/ChargeConnector/:ids"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the occupancy for a charge connectors with a given id (sourcesystemplaceid)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "700cd2a1-f2ce-45ce-961a-b31914c90c3b"
            }
          ]
        }
      ]
    },
    {
      "name": "Place",
      "item": [
        {
          "id": "f7e98957-5160-48fe-a211-7b1c56a2f29a",
          "name": "Place_GetByGeoBox",
          "request": {
            "url": "http://api.tfl.gov.uk/Place?activeOnly=%7B%7D&bbBoxpoints.neLat=%7B%7D&bbBoxpoints.neLon=%7B%7D&bbBoxpoints.swLat=%7B%7D&bbBoxpoints.swLon=%7B%7D&categories=%7B%7D&includeChildren=%7B%7D&type=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the places that lie within the bounding box defined by the lat/lon of its north-west and south-east corners. optionally filters\r\n            on type and can strip properties for a smaller payload.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "824a3e1f-4774-40af-817a-7172e75fae72"
            }
          ]
        },
        {
          "id": "49fc28f1-c211-4de9-a8e4-cca070334548",
          "name": "Place_GetStreetsByPostCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Place/Address/Streets/:Postcode"
              ],
              "query": [
                {
                  "key": "postcodeInput.postcode",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "Postcode",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "postcode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the set of streets associated with a post code.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f9678ad-d7f5-4555-8644-2a81ca461fad"
            }
          ]
        },
        {
          "id": "67183d0a-d1e8-4b66-827e-83032c860bb1",
          "name": "Place_MetaCategories",
          "request": {
            "url": "http://api.tfl.gov.uk/Place/Meta/Categories",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the available place property categories and keys.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09e153d2-9c7b-425d-bd91-b5533f8f8d60"
            }
          ]
        },
        {
          "id": "6c748aa5-0316-4956-a5e9-665fd462d075",
          "name": "Place_MetaPlaceTypes",
          "request": {
            "url": "http://api.tfl.gov.uk/Place/Meta/PlaceTypes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of the available types of place.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "926380a0-4670-4b1f-8a42-60bfb22b3eca"
            }
          ]
        },
        {
          "id": "ed85e5a2-3074-491f-92a6-5d268c2b8295",
          "name": "Place_Search",
          "request": {
            "url": "http://api.tfl.gov.uk/Place/Search?name=%7B%7D&types=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all places that matches the given query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69c2153a-091f-43e6-bb0a-4612bb5cd063"
            }
          ]
        },
        {
          "id": "75183771-434f-49b3-b753-d0921f0a5cb6",
          "name": "Place_GetByType",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Place/Type/:types"
              ],
              "query": [
                {
                  "key": "activeOnly",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "types",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all places of a given type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f516f6c-8b6b-40d6-b0e5-7cc9e64cd207"
            }
          ]
        },
        {
          "id": "28981d85-08bb-4382-a4a8-0902a37c6892",
          "name": "Place_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Place/:id"
              ],
              "query": [
                {
                  "key": "includeChildren",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the place with the given id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29886d19-82d2-4b9b-80da-29ed25597f40"
            }
          ]
        },
        {
          "id": "8d471f93-c5c9-4ea7-b06a-b8054e162fcb",
          "name": "Place_GetAt",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Place/:type/At/:Lat/:Lon"
              ],
              "query": [
                {
                  "key": "location.lat",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "location.lon",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "Lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "Lon",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "type",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lon",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets any places of the given type whose geography intersects the given latitude and longitude. in practice this means the place\r\n            must be polygonal e.g. a boroughboundary.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61943cd4-cf2f-4002-a958-75b58df08bd8"
            }
          ]
        },
        {
          "id": "1d80b519-7829-4d3b-a571-89d5d833612c",
          "name": "Place_GetOverlay",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Place/:type/overlay/:z/:Lat/:Lon/:width/:height"
              ],
              "query": [
                {
                  "key": "location.lat",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "location.lon",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "height",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "Lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "Lon",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "type",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "width",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "z",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lon",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the place overlay for a given set of co-ordinates and a given width/height.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "584eccf7-b809-4992-bd74-d9a83d104b2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Road",
      "item": [
        {
          "id": "0195841e-1dd3-4261-b63d-f487ba1ade49",
          "name": "Road.get",
          "request": {
            "url": "http://api.tfl.gov.uk/Road",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all roads managed by tfl."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "855cc176-2a84-43f7-b42d-1c2eb56a63f0"
            }
          ]
        },
        {
          "id": "22e910c8-84e3-472a-9373-26c7f15565ad",
          "name": "Road_MetaCategories",
          "request": {
            "url": "http://api.tfl.gov.uk/Road/Meta/Categories",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid roaddisruption categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52c34467-3eb6-45ca-8141-e64bc0f50508"
            }
          ]
        },
        {
          "id": "0333b6ef-8d14-4b52-9c13-2ce7b3b9af3b",
          "name": "Road_MetaSeverities",
          "request": {
            "url": "http://api.tfl.gov.uk/Road/Meta/Severities",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid roaddisruption severity codes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12c989f3-f7ee-44e7-8835-5252278ad7e0"
            }
          ]
        },
        {
          "id": "3c60e841-7af1-4363-9788-1061b974d366",
          "name": "Road_DisruptionById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Road/all/Disruption/:disruptionIds"
              ],
              "query": [
                {
                  "key": "stripContent",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "disruptionIds",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of active disruptions filtered by disruption ids.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "782ffb59-262d-4fc0-9232-b166e42cfa4b"
            }
          ]
        },
        {
          "id": "3e407330-ad56-4cd4-907a-7433259fa218",
          "name": "Road_DisruptedStreets",
          "request": {
            "url": "http://api.tfl.gov.uk/Road/all/Street/Disruption?endDate=%7B%7D&startDate=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of disrupted streets. if no date filters are provided, current disruptions are returned.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d272fe87-cb76-49c8-9857-9553c776410f"
            }
          ]
        },
        {
          "id": "225d9023-a7e4-46ac-860d-842a13ae78ba",
          "name": "Road.ids.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Road/:ids"
              ],
              "variable": [
                {
                  "id": "ids",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the road with the specified id (e.g. a1)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b3767ef-2577-41b5-afc4-d15d5163f4e0"
            }
          ]
        },
        {
          "id": "b9711be0-87be-4671-a5e6-5d3973191f57",
          "name": "Road_Disruption",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Road/:ids/Disruption"
              ],
              "query": [
                {
                  "key": "categories",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "closures",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "severities",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "stripContent",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "