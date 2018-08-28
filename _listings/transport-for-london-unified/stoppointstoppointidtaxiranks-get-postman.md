{
  "info": {
    "name": "Transport for London Unified Stop Point stop Point Id  Taxi Ranks",
    "_postman_id": "d22c597d-8999-4d7f-b776-e3e550b3859c",
    "description": "Gets a list of taxi ranks corresponding to the given stop point id..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accent",
      "item": [
        {
          "id": "27768cf4-5186-460d-9f76-4bfff6f3bfbd",
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
              "id": "c4a56450-4a4e-432b-8437-3bd07dcccf1a"
            }
          ]
        }
      ]
    },
    {
      "name": "Air",
      "item": [
        {
          "id": "3e77f536-1c66-42de-a78a-e803024c6ff6",
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
              "id": "766f00bb-0cde-4f74-a475-437397ce4d49"
            }
          ]
        }
      ]
    },
    {
      "name": "Bike",
      "item": [
        {
          "id": "0efd76af-9649-4e64-86c8-222423e4630e",
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
              "id": "529c3a86-acaa-4c00-9044-2c78369d034c"
            }
          ]
        },
        {
          "id": "11ead81b-4962-49e4-b981-4ae9e0e0a245",
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
              "id": "56572441-b906-4479-86a7-6a58a62f346f"
            }
          ]
        },
        {
          "id": "5e09e563-1f55-4c53-8c1d-e6628b05a2eb",
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
              "id": "a0039926-9ff6-402d-bd2d-9270be175249"
            }
          ]
        }
      ]
    },
    {
      "name": "Cabwise",
      "item": [
        {
          "id": "a20700a2-bc04-4482-83f2-ad6930f362ff",
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
              "id": "c6f1d1a7-51d9-44d4-89a1-6fc7b1ded5b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Journey",
      "item": [
        {
          "id": "2e92eb77-6a08-4004-8458-ea9802649628",
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
              "id": "93e34868-fc96-4dcf-a6e6-ac89e30c82ca"
            }
          ]
        },
        {
          "id": "3119b049-c590-46a0-bc2b-4822d2c4752c",
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
              "id": "ab5f958d-c45b-4cb2-8e24-48ebf7ccf302"
            }
          ]
        }
      ]
    },
    {
      "name": "Line",
      "item": [
        {
          "id": "c55fef12-70ea-4aab-bcc1-b5d478f9c649",
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
              "id": "719d8def-77c8-446a-bc72-6c0a67ebc388"
            }
          ]
        },
        {
          "id": "aa4c86fe-37a6-4e0f-b67a-8379b723080d",
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
              "id": "0b6fedb6-fdd3-4ee8-8951-2d57790c9a8b"
            }
          ]
        },
        {
          "id": "6e2af370-134e-4a59-9b03-d6640a2c2482",
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
              "id": "823ba12b-9551-4fed-a321-b780724054e9"
            }
          ]
        },
        {
          "id": "1c2058c3-46ad-44b3-9b2b-3fd1396a5f51",
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
              "id": "29c4c2ae-e5f0-47a9-9ef8-d9db946fe1de"
            }
          ]
        },
        {
          "id": "444c5412-0176-4206-b92d-dc69abc0025d",
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
              "id": "1727e416-311f-4341-9639-59d786ed78dc"
            }
          ]
        },
        {
          "id": "c8610c35-5a63-4dec-be5c-f081cde4f61e",
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
              "id": "aa16cdc3-bb13-474f-9cc8-a974cdf142ac"
            }
          ]
        },
        {
          "id": "735f9a56-5636-44d4-9541-9e4dddb249de",
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
              "id": "228ffecd-7750-445c-9428-e9ca96a6d874"
            }
          ]
        },
        {
          "id": "c11cfd95-05b8-42c5-8e38-7d4852f06065",
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
              "id": "47f590e1-86a0-487f-99b3-91c10372fc94"
            }
          ]
        },
        {
          "id": "69052d47-1aaa-4095-93a6-bedeec791f3b",
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
              "id": "90e582ad-ac3a-49eb-9043-1db1a4699352"
            }
          ]
        },
        {
          "id": "b49396b6-e136-46bf-ade4-8f686be53c07",
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
              "id": "57891e6a-b5df-4142-a39c-3df5eb289536"
            }
          ]
        },
        {
          "id": "b241f2e6-d13f-4c68-abe5-4446323cc6ae",
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
              "id": "ee59cd45-a074-4c53-a1f5-ab0e9649d29e"
            }
          ]
        },
        {
          "id": "1e9b8d0d-0757-49a5-8242-7203dd28654a",
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
              "id": "dec56cbf-d529-4466-a307-a2219a036d6a"
            }
          ]
        },
        {
          "id": "db11da8d-6331-4f17-bc1d-178864779fe7",
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
              "id": "ee8d2c32-6b83-41f7-97c1-6ef5d39ad4d3"
            }
          ]
        },
        {
          "id": "2333e2da-4ab1-4905-b4da-8591d6dee999",
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
              "id": "0ccda18d-71fd-4181-b380-c858a7b01302"
            }
          ]
        },
        {
          "id": "2d6fb6d7-57e5-4ba2-9c74-0620425ecf86",
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
              "id": "be0cfaa3-1ab9-4557-b7a4-2b06d2b14775"
            }
          ]
        },
        {
          "id": "59f79ef2-51f4-42bb-b16f-fc138daf3189",
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
              "id": "96a6b8be-7df9-4074-b804-a2d799f64980"
            }
          ]
        },
        {
          "id": "ee42638b-a81a-4760-92bf-fc8f8f328082",
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
              "id": "68cfb61f-2a5b-46d7-ae06-07c2e61aefbf"
            }
          ]
        },
        {
          "id": "e57a90c0-9eae-42cd-bb3e-dce5bc5bc689",
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
              "id": "794802d0-bcd9-41bd-8254-b0ecac1e21eb"
            }
          ]
        },
        {
          "id": "0ac9fd0b-850c-42e8-a0e5-f01b1456687a",
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
              "id": "6c907744-7720-4f30-b9e1-94eb4331174a"
            }
          ]
        },
        {
          "id": "27909979-b5bf-4423-b42b-1638f0126f50",
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
              "id": "f4c11de2-3976-4846-af8f-25add2506017"
            }
          ]
        },
        {
          "id": "289bc8ab-1f61-440a-b87f-a3c93a31a662",
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
              "id": "b45ebd80-b8ef-4c41-9446-377ced8d134e"
            }
          ]
        }
      ]
    },
    {
      "name": "Mode",
      "item": [
        {
          "id": "ad186a21-2787-4de5-b6bd-509a0a9f4eef",
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
              "id": "18bb940c-6ffe-4364-b9d6-753a08d7cee8"
            }
          ]
        },
        {
          "id": "6270e5da-5a75-4805-9820-01c5d4126707",
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
              "id": "14281515-e196-48ba-8688-2a1d21447e00"
            }
          ]
        }
      ]
    },
    {
      "name": "Occupancy",
      "item": [
        {
          "id": "1a188dea-dbff-43ba-a156-7647dc101c32",
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
              "id": "448de592-0470-4f4b-9d4f-0a95ce4ca9d1"
            }
          ]
        },
        {
          "id": "77b01b13-aaaa-459e-ab03-9a0aa4356eaa",
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
              "id": "38cdd4c0-8921-40a2-93cd-54b2e747c57a"
            }
          ]
        },
        {
          "id": "72390075-7319-4174-a571-1305c55fb015",
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
              "id": "db63eedb-5c6b-4a80-b043-3778e0762283"
            }
          ]
        },
        {
          "id": "fffbd012-0199-4896-8e9f-e453391fd063",
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
              "id": "587b36c4-2a72-4618-9a4c-c7514ceeeccb"
            }
          ]
        },
        {
          "id": "d6283d39-b52f-4f98-a347-df76068b74ff",
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
              "id": "b2bd4740-276e-4a68-8e22-5775fe5fcaf8"
            }
          ]
        }
      ]
    },
    {
      "name": "Place",
      "item": [
        {
          "id": "34bf7868-0a51-492b-bf07-77d597b19329",
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
              "id": "fd174aab-89a8-4ff0-9802-991df3c03a3b"
            }
          ]
        },
        {
          "id": "219811af-dcce-4ada-befd-1a7265a8aad0",
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
              "id": "a9c91f52-ad9a-40f9-aa9a-cb307f33149b"
            }
          ]
        },
        {
          "id": "c646836c-4bed-481d-b3d3-1c1ccd0a2a14",
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
              "id": "75a7de9f-9f2b-4b25-876a-5baa4c4d7ef3"
            }
          ]
        },
        {
          "id": "d026fd5c-6ed5-4706-a8d6-dc0deba4ac86",
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
              "id": "a2765a76-af70-441a-abcf-72d51e30c259"
            }
          ]
        },
        {
          "id": "7d8b64a7-4ed9-4da2-be4d-8b8a1ea49a84",
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
              "id": "9da3fc78-9514-4ce1-854a-b60ca841b1e9"
            }
          ]
        },
        {
          "id": "7bddb484-8768-4db7-868f-fa165df79ce3",
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
              "id": "906cb5e9-ea8e-40f1-b81a-118ea34d3d9c"
            }
          ]
        },
        {
          "id": "8de61398-293c-4175-bac3-c948dc05cac0",
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
              "id": "b0e5b1fb-a91b-4e98-bbf7-f05761ed362f"
            }
          ]
        },
        {
          "id": "cc0f4afd-68bb-4398-9703-e027df71c610",
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
              "id": "89bc695f-fc08-4504-a494-8a41b2f7f4e8"
            }
          ]
        },
        {
          "id": "c9967ba1-310e-4837-96ee-7587a854b9dd",
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
              "id": "af53a640-5c5e-4e59-9d2f-f741cba90702"
            }
          ]
        }
      ]
    },
    {
      "name": "Road",
      "item": [
        {
          "id": "a77da246-43a2-46db-90c8-a1699035534e",
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
              "id": "6d64271e-ccf9-43bd-a11e-99b9b692fef7"
            }
          ]
        },
        {
          "id": "bbdc6d56-05c9-4390-a835-2580457cb337",
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
              "id": "1f316cee-a529-4561-8a7b-1cd2b0edcac4"
            }
          ]
        },
        {
          "id": "56f61105-5f9b-426c-baa8-fe4438027b49",
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
              "id": "760469f3-37fe-4be7-ac0a-39a08f2517f0"
            }
          ]
        },
        {
          "id": "ab9c7cb5-d490-4d86-9351-9500130bffb0",
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
              "id": "a22f64b9-650e-41c3-9fab-3621ef347c34"
            }
          ]
        },
        {
          "id": "21010e0e-143f-4f0d-9556-e3e3d4030ede",
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
              "id": "2ce55223-0790-45e2-8aaa-974f29c891fd"
            }
          ]
        },
        {
          "id": "efbc9195-222f-46bd-958c-d8ab077842b8",
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
              "id": "42ddbd79-e75d-445e-a8b2-1b9b9ea4ceb5"
            }
          ]
        },
        {
          "id": "3d1da9bc-2ab5-41d8-9235-d140f3eb3e4d",
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
               