{
  "info": {
    "name": "Transport for London Unified Stop Point  Crowding line",
    "_postman_id": "b44c7050-d20b-40ad-b95e-c9a6f3188286",
    "description": "Gets all the crowding data (static) for the stoppointid, plus crowding data for a given line and optionally a particular direction..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accent",
      "item": [
        {
          "id": "28ee6766-4aa8-4895-afd4-b6314a77ec76",
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
              "id": "0f5fd1c7-2c50-421a-b45a-9f5bf34f2637"
            }
          ]
        }
      ]
    },
    {
      "name": "Air",
      "item": [
        {
          "id": "1dd299bc-e688-4582-a53d-f889292c6e47",
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
              "id": "8e93ed45-155e-47db-a99d-e99913d372fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Bike",
      "item": [
        {
          "id": "6214545f-093e-445c-93c5-fc2f8836942c",
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
              "id": "4531e651-5b94-484b-8a07-38dde252da28"
            }
          ]
        },
        {
          "id": "5500a70a-3007-4f1d-bf7c-4c0c2c8a6f2a",
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
              "id": "76737b55-8e7b-4ce4-9168-29ea7ac86795"
            }
          ]
        },
        {
          "id": "f7a02db9-2d97-432c-9872-bdc253435e4a",
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
              "id": "f73d55b4-ae0e-43a4-8f33-0062bed01492"
            }
          ]
        }
      ]
    },
    {
      "name": "Cabwise",
      "item": [
        {
          "id": "ec84ee76-d69c-4668-a454-a6d477bd743b",
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
              "id": "9738bbec-7365-40da-9bb7-5cce4b22666f"
            }
          ]
        }
      ]
    },
    {
      "name": "Journey",
      "item": [
        {
          "id": "89f89e05-e794-4e7c-bf8b-e0dc58bcce6f",
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
              "id": "ec87838a-4a05-4239-b72a-45b871889a2c"
            }
          ]
        },
        {
          "id": "34e40c5f-b8fa-45f8-b4fb-7dafe5deb41f",
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
              "id": "98bf57c9-b786-4422-af24-d5915ec7d561"
            }
          ]
        }
      ]
    },
    {
      "name": "Line",
      "item": [
        {
          "id": "697b86f3-34e8-45d9-bfff-9b217d7bc202",
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
              "id": "c62dfcc2-2806-41c0-ac8c-9aca1f138728"
            }
          ]
        },
        {
          "id": "21b6f2e6-aa7f-481e-8717-ee51da79b81f",
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
              "id": "8a5ac41a-7e1f-4769-9ea2-64c1bbaea116"
            }
          ]
        },
        {
          "id": "68d75aff-2640-432a-95ae-b7cfc247039c",
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
              "id": "0ea5dc56-f618-4128-adad-e98f3c5294aa"
            }
          ]
        },
        {
          "id": "8387af90-23ab-454c-924e-eacf4da92914",
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
              "id": "a0579e08-1c15-444d-825f-3a671d7bf599"
            }
          ]
        },
        {
          "id": "bd587e49-3991-4281-998e-1b4ef3265944",
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
              "id": "b52a17c5-285b-4bc3-82e8-02d03a74e52c"
            }
          ]
        },
        {
          "id": "1e4005ee-626f-4511-8c7b-b558206c7904",
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
              "id": "249cbffe-e3e7-45fc-9e2e-027c78346ef0"
            }
          ]
        },
        {
          "id": "9a7541c2-0c92-4f74-b365-0ab8b9f51158",
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
              "id": "722c4b51-6b7a-43c1-9cf5-7423d31b2813"
            }
          ]
        },
        {
          "id": "6493e8aa-0b24-4dac-9165-a8cfbe254e0b",
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
              "id": "20e9943f-d09d-43a4-a8d5-98773f9748f2"
            }
          ]
        },
        {
          "id": "e1e327bc-85b0-4203-af3f-28ae58be6674",
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
              "id": "e56608a2-a3bd-4cc2-8eff-a41dd8981683"
            }
          ]
        },
        {
          "id": "167cf278-4dc8-47c3-b5b0-683bd81d21cf",
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
              "id": "8f261c6b-4a69-4108-9b9e-f3733f879f98"
            }
          ]
        },
        {
          "id": "3bfeaeca-0ea9-4a4a-8e91-c8e04f846f85",
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
              "id": "c6ba1b8f-e83c-4e6d-848a-5606bf20160d"
            }
          ]
        },
        {
          "id": "0ff749c5-a5e8-4797-a0d2-cbb62f504732",
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
              "id": "debc64fc-2449-4544-9e40-3d0d11f24a89"
            }
          ]
        },
        {
          "id": "9c953172-3294-4f1e-8f61-be60855210cf",
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
              "id": "06e56af4-106b-4864-9874-8a08d9656822"
            }
          ]
        },
        {
          "id": "d293c5c7-cefb-4c14-803d-0e725ac2a68c",
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
              "id": "e00bcda2-05cf-42b2-a7ea-9f5142816da4"
            }
          ]
        },
        {
          "id": "f464980f-ae3d-4844-bc75-1d76c3f3715f",
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
              "id": "abed96f3-bbe1-492f-9c8f-80344d26ab78"
            }
          ]
        },
        {
          "id": "e3a89d08-0656-4cfb-8b14-05e941977fd2",
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
              "id": "b02c5342-1b4d-4925-a595-13fc00484748"
            }
          ]
        },
        {
          "id": "5585a626-a72b-45d3-b75a-545f7e4f0d90",
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
              "id": "f73db64c-ffb1-45d5-942c-0fc531e81b60"
            }
          ]
        },
        {
          "id": "c95c339b-ec9c-4368-a49d-b887dea3e672",
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
              "id": "b031a82c-7e86-4b4a-8a99-4943fade777d"
            }
          ]
        },
        {
          "id": "e24965eb-61f0-472a-84be-d83cac38e5d2",
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
              "id": "d9213740-06bf-481f-a43a-a15c9b37f4fc"
            }
          ]
        },
        {
          "id": "904f56b3-5b37-4562-bc94-3cd8b8e2b491",
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
              "id": "94757621-9415-43b3-a88c-aa0ec7dced40"
            }
          ]
        },
        {
          "id": "a7ecd9a4-d00d-4138-a2d4-37d3acbe5378",
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
              "id": "dc7d7850-00f0-45de-8002-5fa01f610249"
            }
          ]
        }
      ]
    },
    {
      "name": "Mode",
      "item": [
        {
          "id": "6d332fa7-a217-4029-a3b4-b4a4c1e41ddf",
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
              "id": "db938319-fdfa-42f2-af41-efa516f9536b"
            }
          ]
        },
        {
          "id": "41a7ddc1-3f29-482a-bd64-f0c073f71b8d",
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
              "id": "513bbcff-1340-485d-b94f-10c5a97b4518"
            }
          ]
        }
      ]
    },
    {
      "name": "Occupancy",
      "item": [
        {
          "id": "a4604190-0f8a-403f-b80b-dacb28a9460a",
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
              "id": "fe3212cf-2dd7-4f79-a05f-1322ade0fcb5"
            }
          ]
        },
        {
          "id": "7f4f2263-86c2-4966-bcf9-a94c235e0409",
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
              "id": "a66553f5-f7cc-4bb8-9064-98fb13ec3115"
            }
          ]
        },
        {
          "id": "aad85346-4461-46b6-90ef-c558367b1d7d",
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
              "id": "4ef0eb6b-e2ec-4e1b-8744-bd0d80e2d419"
            }
          ]
        },
        {
          "id": "d7da0d78-49ba-4a21-aebb-f81b32b713d4",
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
              "id": "905658cb-8f01-4591-b99f-69bd5011e8c1"
            }
          ]
        },
        {
          "id": "23a16e7e-2fbb-4f25-a892-751551c2179a",
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
              "id": "9d42f340-1534-4bb9-acf5-be90992da5e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Place",
      "item": [
        {
          "id": "55f18116-0ba8-4c70-8d1a-03ce7d59c0a5",
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
              "id": "ecc6ae94-53d1-4e0f-96fb-54f184299bab"
            }
          ]
        },
        {
          "id": "9a464e32-fd0a-4f38-a0a5-8db5e95b19ba",
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
              "id": "eca70e73-63af-480f-89d3-c534e53bcc0f"
            }
          ]
        },
        {
          "id": "37d4951a-cf3c-4775-a034-ec4c8b57bc88",
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
              "id": "c1801e5b-a2ca-45dd-af80-dd69e9c41a7d"
            }
          ]
        },
        {
          "id": "0c3a631e-1729-4e98-b1c1-c6e1bf9a3853",
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
              "id": "b00c4f27-65ec-4b72-b0a2-52e058401b70"
            }
          ]
        },
        {
          "id": "cbecd156-de29-4286-83ef-a121496b85de",
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
              "id": "b5129232-1ea3-4ce7-b748-818af38c0213"
            }
          ]
        },
        {
          "id": "6863b8ae-103a-4fa6-b7b1-7acd4341ddef",
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
              "id": "19c69b69-472c-4be1-b58e-a05b241bf956"
            }
          ]
        },
        {
          "id": "80c37bb4-dee0-4213-b4dd-4b727a5d566b",
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
              "id": "51fe2a99-f9b5-4b42-8127-571b614e70d7"
            }
          ]
        },
        {
          "id": "a8a97f5d-fbd8-4165-b7d3-4b0c88011ec1",
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
              "id": "79d2ae12-8a11-4847-b5f7-10a244ae05ea"
            }
          ]
        },
        {
          "id": "bb696222-3b14-450e-9e4c-92ef1d7422cd",
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
              "id": "62cdfb10-2fa0-42ea-8c48-56768847b4a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Road",
      "item": [
        {
          "id": "2b84d1ab-ea1d-4a1b-9f18-b039df42b351",
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
              "id": "ab3a52c6-208d-420c-bb98-d02346b6e421"
            }
          ]
        },
        {
          "id": "d1dbca9c-4932-4565-9c26-85fb6ec4e9cc",
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
              "id": "837a7e36-7081-4299-9c25-10661b865aa7"
            }
          ]
        },
        {
          "id": "9c931fe2-ead7-4d0f-91d3-c0ef8a593ea5",
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
              "id": "72225761-0efb-4f96-943c-535976cc980e"
            }
          ]
        },
        {
          "id": "d5b00e20-a4b4-40fb-ba03-26652e40a0e4",
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
              "id": "2949433e-0b33-4126-85bf-ba3c5a7c71a2"
            }
          ]
        },
        {
          "id": "4dfd537a-31ac-4e7a-bf3b-79529d29126c",
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
              "id": "7d8bd57a-f54e-4c79-8322-88730a49e40a"
            }
          ]
        },
        {
          "id": "5d026581-3b46-408b-8c4c-4a9b6c30b062",
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
              "id": "6dd773a4-11f0-4094-a8db-0d76506ba8f2"
            }
          ]
        },
        {
          "id": "95ebeb34-d9f2-4380-a846-a815d6b22e40",
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
          