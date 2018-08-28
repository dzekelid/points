---
name: Transport for London Unified
x-slug: transport-for-london-unified
description: We are the integrated transport authority responsible for delivering
  Mayor of London Sadiq Khans strategy and commitments on transport. We run the day-to-day
  operation of the Capitals public transport network and manage Londons main roads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Points
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/apis.md
specificationVersion: "0.14"
apis:
- name: Transport for London Unified - Line  Stop Points
  x-api-slug: lineidstoppoints-get
  description: Gets a list of the stations that serve the given line id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidstoppoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidstoppoints-get-openapi.md
- name: Transport for London Unified - Occupancy  Bike Points s
  x-api-slug: occupancybikepointsids-get
  description: Get the occupancy for bike points..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/occupancybikepointsids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/occupancybikepointsids-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepoint-get
  description: "Gets all bike point locations. the place object has an addtionalproperties
    array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
    which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
    - (nbbikes + nbspa."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-openapi.md
- name: Transport for London Unified - Bike Point  Search
  x-api-slug: bikepointsearch-get
  description: "Search for bike stations by their name, a bike point's name often
    contains information about the name of the street\r\n            or nearby landmarks,
    for example. note that the search result does not contain the placeproperties
    i.e. the status\r\n     ."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepointid-get
  description: Gets the bike point with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-openapi.md
- name: Transport for London Unified - Line s  Arrivals stop Point Id
  x-api-slug: lineidsarrivalsstoppointid-get
  description: Get the list of arrival predictions for given line ids based at the
    given stop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id
  x-api-slug: lineidtimetablefromstoppointid-get
  description: Gets the timetable for a specified station on the give line.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id to to Stop
    Point Id
  x-api-slug: lineidtimetablefromstoppointidtotostoppointid-get
  description: Gets the timetable for a specified station on the give line with specified
    destination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point
  x-api-slug: stoppoint-get
  description: Gets a list of stoppoints within {radius} by the specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Categories
  x-api-slug: stoppointmetacategories-get
  description: Gets the list of available stoppoint additional information categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Modes
  x-api-slug: stoppointmetamodes-get
  description: Gets the list of available stoppoint modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Stop Types
  x-api-slug: stoppointmetastoptypes-get
  description: Gets the list of available stoppoint types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Search
  x-api-slug: stoppointsearch-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-openapi.md
- name: Transport for London Unified - Stop Point  Search query
  x-api-slug: stoppointsearchquery-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-openapi.md
- name: Transport for London Unified - Stop Point  Service Types
  x-api-slug: stoppointservicetypes-get
  description: Gets the service types for a given stoppoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Sms
  x-api-slug: stoppointsmsid-get
  description: Gets a stoppoint for a given sms code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-openapi.md
- name: Transport for London Unified - Stop Point  Type types
  x-api-slug: stoppointtypetypes-get
  description: Gets all stop points of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-openapi.md
- name: Transport for London Unified - Stop Point s
  x-api-slug: stoppointids-get
  description: Gets a list of stoppoints corresponding to the given list of stop ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-openapi.md
- name: Transport for London Unified - Stop Point s  Disruption
  x-api-slug: stoppointidsdisruption-get
  description: Gets all disruptions for the specified stoppointid, plus disruptions
    for any child naptan records it may have..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Arrivals
  x-api-slug: stoppointidarrivals-get
  description: Gets the list of arrival predictions for the given stop point id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-openapi.md
- name: Transport for London Unified - Stop Point  Can Reach On Line line Id
  x-api-slug: stoppointidcanreachonlinelineid-get
  description: Gets stopoints that are reachable from a station/line combination..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-openapi.md
- name: Transport for London Unified - Stop Point  Crowding line
  x-api-slug: stoppointidcrowdingline-get
  description: Gets all the crowding data (static) for the stoppointid, plus crowding
    data for a given line and optionally a particular direction..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-openapi.md
- name: Transport for London Unified - Stop Point  Direction To to Stop Point Id
  x-api-slug: stoppointiddirectiontotostoppointid-get
  description: Returns the canonical direction, "inbound" or "outbound", for a given
    pair of stop point ids in the direction from -&gt; to..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point  Route
  x-api-slug: stoppointidroute-get
  description: Returns the route sections for all the lines that service the given
    stop point ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Car Parks
  x-api-slug: stoppointstoppointidcarparks-get
  description: Get car parks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Taxi Ranks
  x-api-slug: stoppointstoppointidtaxiranks-get
  description: Gets a list of taxi ranks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepoint-get
  description: "Gets all bike point locations. the place object has an addtionalproperties
    array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
    which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
    - (nbbikes + nbspa."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-openapi.md
- name: Transport for London Unified - Bike Point  Search
  x-api-slug: bikepointsearch-get
  description: "Search for bike stations by their name, a bike point's name often
    contains information about the name of the street\r\n            or nearby landmarks,
    for example. note that the search result does not contain the placeproperties
    i.e. the status\r\n     ."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepointid-get
  description: Gets the bike point with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-openapi.md
- name: Transport for London Unified - Line s  Arrivals stop Point Id
  x-api-slug: lineidsarrivalsstoppointid-get
  description: Get the list of arrival predictions for given line ids based at the
    given stop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id
  x-api-slug: lineidtimetablefromstoppointid-get
  description: Gets the timetable for a specified station on the give line.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id to to Stop
    Point Id
  x-api-slug: lineidtimetablefromstoppointidtotostoppointid-get
  description: Gets the timetable for a specified station on the give line with specified
    destination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point
  x-api-slug: stoppoint-get
  description: Gets a list of stoppoints within {radius} by the specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Categories
  x-api-slug: stoppointmetacategories-get
  description: Gets the list of available stoppoint additional information categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Modes
  x-api-slug: stoppointmetamodes-get
  description: Gets the list of available stoppoint modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Stop Types
  x-api-slug: stoppointmetastoptypes-get
  description: Gets the list of available stoppoint types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Search
  x-api-slug: stoppointsearch-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-openapi.md
- name: Transport for London Unified - Stop Point  Search query
  x-api-slug: stoppointsearchquery-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-openapi.md
- name: Transport for London Unified - Stop Point  Service Types
  x-api-slug: stoppointservicetypes-get
  description: Gets the service types for a given stoppoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Sms
  x-api-slug: stoppointsmsid-get
  description: Gets a stoppoint for a given sms code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-openapi.md
- name: Transport for London Unified - Stop Point  Type types
  x-api-slug: stoppointtypetypes-get
  description: Gets all stop points of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-openapi.md
- name: Transport for London Unified - Stop Point s
  x-api-slug: stoppointids-get
  description: Gets a list of stoppoints corresponding to the given list of stop ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-openapi.md
- name: Transport for London Unified - Stop Point s  Disruption
  x-api-slug: stoppointidsdisruption-get
  description: Gets all disruptions for the specified stoppointid, plus disruptions
    for any child naptan records it may have..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Arrivals
  x-api-slug: stoppointidarrivals-get
  description: Gets the list of arrival predictions for the given stop point id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-openapi.md
- name: Transport for London Unified - Stop Point  Can Reach On Line line Id
  x-api-slug: stoppointidcanreachonlinelineid-get
  description: Gets stopoints that are reachable from a station/line combination..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-openapi.md
- name: Transport for London Unified - Stop Point  Crowding line
  x-api-slug: stoppointidcrowdingline-get
  description: Gets all the crowding data (static) for the stoppointid, plus crowding
    data for a given line and optionally a particular direction..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-openapi.md
- name: Transport for London Unified - Stop Point  Direction To to Stop Point Id
  x-api-slug: stoppointiddirectiontotostoppointid-get
  description: Returns the canonical direction, "inbound" or "outbound", for a given
    pair of stop point ids in the direction from -&gt; to..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point  Route
  x-api-slug: stoppointidroute-get
  description: Returns the route sections for all the lines that service the given
    stop point ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Car Parks
  x-api-slug: stoppointstoppointidcarparks-get
  description: Get car parks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Taxi Ranks
  x-api-slug: stoppointstoppointidtaxiranks-get
  description: Gets a list of taxi ranks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Taxi Ranks
  x-api-slug: stoppointstoppointidtaxiranks-get
  description: Gets a list of taxi ranks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Car Parks
  x-api-slug: stoppointstoppointidcarparks-get
  description: Get car parks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Route
  x-api-slug: stoppointidroute-get
  description: Returns the route sections for all the lines that service the given
    stop point ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidroute-get-openapi.md
- name: Transport for London Unified - Stop Point  Direction To to Stop Point Id
  x-api-slug: stoppointiddirectiontotostoppointid-get
  description: Returns the canonical direction, "inbound" or "outbound", for a given
    pair of stop point ids in the direction from -&gt; to..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point  Crowding line
  x-api-slug: stoppointidcrowdingline-get
  description: Gets all the crowding data (static) for the stoppointid, plus crowding
    data for a given line and optionally a particular direction..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-openapi.md
- name: Transport for London Unified - Stop Point  Can Reach On Line line Id
  x-api-slug: stoppointidcanreachonlinelineid-get
  description: Gets stopoints that are reachable from a station/line combination..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-openapi.md
- name: Transport for London Unified - Stop Point  Arrivals
  x-api-slug: stoppointidarrivals-get
  description: Gets the list of arrival predictions for the given stop point id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidarrivals-get-openapi.md
- name: Transport for London Unified - Stop Point s  Disruption
  x-api-slug: stoppointidsdisruption-get
  description: Gets all disruptions for the specified stoppointid, plus disruptions
    for any child naptan records it may have..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point s
  x-api-slug: stoppointids-get
  description: Gets a list of stoppoints corresponding to the given list of stop ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointids-get-openapi.md
- name: Transport for London Unified - Stop Point  Type types
  x-api-slug: stoppointtypetypes-get
  description: Gets all stop points of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointtypetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Sms
  x-api-slug: stoppointsmsid-get
  description: Gets a stoppoint for a given sms code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsmsid-get-openapi.md
- name: Transport for London Unified - Stop Point  Service Types
  x-api-slug: stoppointservicetypes-get
  description: Gets the service types for a given stoppoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointservicetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Search query
  x-api-slug: stoppointsearchquery-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearchquery-get-openapi.md
- name: Transport for London Unified - Stop Point  Search
  x-api-slug: stoppointsearch-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointsearch-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Stop Types
  x-api-slug: stoppointmetastoptypes-get
  description: Gets the list of available stoppoint types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Modes
  x-api-slug: stoppointmetamodes-get
  description: Gets the list of available stoppoint modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetamodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Categories
  x-api-slug: stoppointmetacategories-get
  description: Gets the list of available stoppoint additional information categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppointmetacategories-get-openapi.md
- name: Transport for London Unified - Stop Point
  x-api-slug: stoppoint-get
  description: Gets a list of stoppoints within {radius} by the specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/stoppoint-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id to to Stop
    Point Id
  x-api-slug: lineidtimetablefromstoppointidtotostoppointid-get
  description: Gets the timetable for a specified station on the give line with specified
    destination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id
  x-api-slug: lineidtimetablefromstoppointid-get
  description: Gets the timetable for a specified station on the give line.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-openapi.md
- name: Transport for London Unified - Line s  Arrivals stop Point Id
  x-api-slug: lineidsarrivalsstoppointid-get
  description: Get the list of arrival predictions for given line ids based at the
    given stop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepointid-get
  description: Gets the bike point with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointid-get-openapi.md
- name: Transport for London Unified - Bike Point  Search
  x-api-slug: bikepointsearch-get
  description: "Search for bike stations by their name, a bike point's name often
    contains information about the name of the street\r\n            or nearby landmarks,
    for example. note that the search result does not contain the placeproperties
    i.e. the status\r\n     ."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepointsearch-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepoint-get
  description: "Gets all bike point locations. the place object has an addtionalproperties
    array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
    which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
    - (nbbikes + nbspa."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/transport-for-london-unified/bikepoint-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transitfeeds.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transport.for.london.unified.stack.network
- type: x-developer
  url: http://api.tfl.gov.uk
- type: x-website
  url: https://tfl.gov.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---