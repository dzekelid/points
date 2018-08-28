---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Stop Point  Sms
  description: Gets a stoppoint for a given sms code..
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Line/{id}/StopPoints:
    get:
      summary: Line  Stop Points
      description: Gets a list of the stations that serve the given line id.
      operationId: Line_StopPoints
      x-api-path-slug: lineidstoppoints-get
      parameters:
      - in: path
        name: id
        description: A single line id e
      - in: query
        name: tflOperatedNationalRailStationsOnly
        description: If the national-rail line is requested, this flag will filter
          the national rail stations so that only those operated by TfL are returned
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Stop
      - Points
  /Occupancy/BikePoints/{ids}:
    get:
      summary: Occupancy  Bike Points s
      description: Get the occupancy for bike points..
      operationId: Occupancy_GetBikePointsOccupancies
      x-api-path-slug: occupancybikepointsids-get
      parameters:
      - in: path
        name: ids
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Bike
      - Points
      - S
  /BikePoint:
    get:
      summary: Bike Point
      description: "Gets all bike point locations. the place object has an addtionalproperties
        array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
        which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
        - (nbbikes + nbspa."
      operationId: BikePoint_GetAll
      x-api-path-slug: bikepoint-get
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
  /BikePoint/Search:
    get:
      summary: Bike Point  Search
      description: "Search for bike stations by their name, a bike point's name often
        contains information about the name of the street\r\n            or nearby
        landmarks, for example. note that the search result does not contain the placeproperties
        i.e. the status\r\n     ."
      operationId: BikePoint_Search
      x-api-path-slug: bikepointsearch-get
      parameters:
      - in: query
        name: query
        description: The search term e
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
      - ""
      - Search
  /BikePoint/{id}:
    get:
      summary: Bike Point
      description: Gets the bike point with the given id..
      operationId: BikePoint_Get
      x-api-path-slug: bikepointid-get
      parameters:
      - in: path
        name: id
        description: A bike point id (a list of ids can be obtained from the above
          BikePoint call)
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
  /Line/{ids}/Arrivals/{stopPointId}:
    get:
      summary: Line s  Arrivals stop Point Id
      description: Get the list of arrival predictions for given line ids based at
        the given stop.
      operationId: Line_Arrivals
      x-api-path-slug: lineidsarrivalsstoppointid-get
      parameters:
      - in: query
        name: destinationStationId
        description: Optional
      - in: query
        name: direction
        description: Optional
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      - in: path
        name: stopPointId
        description: Optional
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
      - ""
      - Arrivals
      - Stop
      - Point
      - Id
  /Line/{id}/Timetable/{fromStopPointId}:
    get:
      summary: Line  Timetable from Stop Point Id
      description: Gets the timetable for a specified station on the give line.
      operationId: Line_Timetable
      x-api-path-slug: lineidtimetablefromstoppointid-get
      parameters:
      - in: path
        name: fromStopPointId
        description: The originating stations stop point id (station naptan code e
      - in: path
        name: id
        description: A single line id e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Timetable
      - From
      - Stop
      - Point
      - Id
  /Line/{id}/Timetable/{fromStopPointId}/to/{toStopPointId}:
    get:
      summary: Line  Timetable from Stop Point Id to to Stop Point Id
      description: Gets the timetable for a specified station on the give line with
        specified destination.
      operationId: Line_TimetableTo
      x-api-path-slug: lineidtimetablefromstoppointidtotostoppointid-get
      parameters:
      - in: path
        name: fromStopPointId
        description: The originating stations stop point id (station naptan code e
      - in: path
        name: id
        description: A single line id e
      - in: path
        name: toStopPointId
        description: The destination stationss Naptan code
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Timetable
      - From
      - Stop
      - Point
      - Id
      - To
      - To
      - Stop
      - Point
      - Id
  /StopPoint:
    get:
      summary: Stop Point
      description: Gets a list of stoppoints within {radius} by the specified criteria.
      operationId: StopPoint_GetByGeoPoint
      x-api-path-slug: stoppoint-get
      parameters:
      - in: query
        name: categories
        description: an optional list of comma separated property categories to return
          in the StopPoints property bag
      - in: query
        name: location.lat
      - in: query
        name: location.lon
      - in: query
        name: modes
        description: the list of modes to search (comma separated mode names e
      - in: query
        name: radius
        description: 'the radius of the bounding circle in metres (default : 200)'
      - in: query
        name: returnLines
        description: true to return the lines that each stop point serves as a nested
          resource
      - in: query
        name: stopTypes
        description: a list of stopTypes that should be returned (a list of valid
          stop types can be obtained from the StopPoint/meta/stoptypes endpoint)
      - in: query
        name: useStopPointHierarchy
        description: Re-arrange the output into a parent/child hierarchy
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
  /StopPoint/Meta/Categories:
    get:
      summary: Stop Point  Meta  Categories
      description: Gets the list of available stoppoint additional information categories.
      operationId: StopPoint_MetaCategories
      x-api-path-slug: stoppointmetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Categories
  /StopPoint/Meta/Modes:
    get:
      summary: Stop Point  Meta  Modes
      description: Gets the list of available stoppoint modes.
      operationId: StopPoint_MetaModes
      x-api-path-slug: stoppointmetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Modes
  /StopPoint/Meta/StopTypes:
    get:
      summary: Stop Point  Meta  Stop Types
      description: Gets the list of available stoppoint types.
      operationId: StopPoint_MetaStopTypes
      x-api-path-slug: stoppointmetastoptypes-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Stop
      - Types
  /StopPoint/Mode/{modes}:
    get:
      summary: Stop Point  Mode modes
      description: Gets a list of stoppoints filtered by the modes available at that
        stoppoint..
      operationId: StopPoint_GetByMode
      x-api-path-slug: stoppointmodemodes-get
      parameters:
      - in: path
        name: modes
        description: A comma-seperated list of modes e
      - in: query
        name: page
        description: The data set page to return
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Mode
      - Modes
  /StopPoint/Mode/{modes}/Disruption:
    get:
      summary: Stop Point  Mode modes  Disruption
      description: Gets a distinct list of disrupted stop points for the given modes.
      operationId: StopPoint_DisruptionByMode
      x-api-path-slug: stoppointmodemodesdisruption-get
      parameters:
      - in: query
        name: includeRouteBlockedStops
      - in: path
        name: modes
        description: A comma-seperated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Mode
      - Modes
      - ""
      - Disruption
  /StopPoint/Search:
    get:
      summary: Stop Point  Search
      description: Search stoppoints by their common name, or their 5-digit countdown
        bus stop code..
      operationId: StopPoint.Search.get
      x-api-path-slug: stoppointsearch-get
      parameters:
      - in: query
        name: faresOnly
        description: True to only return stations in that have Fares data available
          for single fares to another station
      - in: query
        name: includeHubs
        description: If true, returns results including HUBs
      - in: query
        name: lines
        description: An optional, parameter separated list of the lines to filter
          by
      - in: query
        name: maxResults
        description: An optional result limit, defaulting to and with a maximum of
          50
      - in: query
        name: modes
        description: An optional, parameter separated list of the modes to filter
          by
      - in: query
        name: query
        description: The query string, case-insensitive
      - in: query
        name: tflOperatedNationalRailStationsOnly
        description: If the national-rail mode is included, this flag will filter
          the national rail stations so that only those operated by TfL are returned
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Search
  /StopPoint/Search/{query}:
    get:
      summary: Stop Point  Search query
      description: Search stoppoints by their common name, or their 5-digit countdown
        bus stop code..
      operationId: StopPoint.Search.query.get
      x-api-path-slug: stoppointsearchquery-get
      parameters:
      - in: query
        name: faresOnly
        description: True to only return stations in that have Fares data available
          for single fares to another station
      - in: query
        name: includeHubs
        description: If true, returns results including HUBs
      - in: query
        name: lines
        description: An optional, parameter separated list of the lines to filter
          by
      - in: query
        name: maxResults
        description: An optional result limit, defaulting to and with a maximum of
          50
      - in: query
        name: modes
        description: An optional, parameter separated list of the modes to filter
          by
      - in: path
        name: query
        description: The query string, case-insensitive
      - in: query
        name: tflOperatedNationalRailStationsOnly
        description: If the national-rail mode is included, this flag will filter
          the national rail stations so that only those operated by TfL are returned
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Search
      - Query
  /StopPoint/ServiceTypes:
    get:
      summary: Stop Point  Service Types
      description: Gets the service types for a given stoppoint.
      operationId: StopPoint_GetServiceTypes
      x-api-path-slug: stoppointservicetypes-get
      parameters:
      - in: query
        name: id
        description: The Naptan id of the stop
      - in: query
        name: lineIds
        description: The lines which contain the given Naptan id (all lines relevant
          to the given stoppoint if empty)
      - in: query
        name: modes
        description: The modes which the lines are relevant to (all if empty)
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Service
      - Types
  /StopPoint/Sms/{id}:
    get:
      summary: Stop Point  Sms
      description: Gets a stoppoint for a given sms code..
      operationId: StopPoint_GetBySms
      x-api-path-slug: stoppointsmsid-get
      parameters:
      - in: path
        name: id
        description: A 5-digit Countdown Bus Stop Code e
      - in: query
        name: output
        description: If set to web, a 302 redirect to relevant website bus stop page
          is returned
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Sms
  /StopPoint/Type/{types}:
    get:
      summary: Stop Point  Type types
      description: Gets all stop points of a given type.
      operationId: StopPoint_GetByType
      x-api-path-slug: stoppointtypetypes-get
      parameters:
      - in: path
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Type
      - Types
  /StopPoint/{ids}:
    get:
      summary: Stop Point s
      description: Gets a list of stoppoints corresponding to the given list of stop
        ids..
      operationId: StopPoint.ids.get
      x-api-path-slug: stoppointids-get
      parameters:
      - in: path
        name: ids
        description: A comma-separated list of stop point ids (station naptan code
          e
      - in: query
        name: includeCrowdingData
        description: Include the crowding data (static)
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - S
  /StopPoint/{ids}/Disruption:
    get:
      summary: Stop Point s  Disruption
      description: Gets all disruptions for the specified stoppointid, plus disruptions
        for any child naptan records it may have..
      operationId: StopPoint_Disruption
      x-api-path-slug: stoppointidsdisruption-get
      parameters:
      - in: query
        name: flattenResponse
        description: Specify true to associate all disruptions with parent stop point
      - in: query
        name: getFamily
        description: Specify true to return disruptions for entire family, or false
          to return disruptions for just this stop point
      - in: path
        name: ids
        description: A comma-seperated list of stop point ids
      - in: query
        name: includeRouteBlockedStops
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - S
      - ""
      - Disruption
  /StopPoint/{id}/Arrivals:
    get:
      summary: Stop Point  Arrivals
      description: Gets the list of arrival predictions for the given stop point id.
      operationId: StopPoint_Arrivals
      x-api-path-slug: stoppointidarrivals-get
      parameters:
      - in: path
        name: id
        description: A StopPoint id (station naptan code e
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Arrivals
  /StopPoint/{id}/CanReachOnLine/{lineId}:
    get:
      summary: Stop Point  Can Reach On Line line Id
      description: Gets stopoints that are reachable from a station/line combination..
      operationId: StopPoint_ReachableFrom
      x-api-path-slug: stoppointidcanreachonlinelineid-get
      parameters:
      - in: path
        name: id
        description: The id (station naptan code e
      - in: path
        name: lineId
        description: Line id of the line to filter by (e
      - in: query
        name: serviceTypes
        description: A comma-separated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Can
      - Reach
      - "On"
      - Line
      - Line
      - Id
  /StopPoint/{id}/Crowding/{line}:
    get:
      summary: Stop Point  Crowding line
      description: Gets all the crowding data (static) for the stoppointid, plus crowding
        data for a given line and optionally a particular direction..
      operationId: StopPoint_Crowding
      x-api-path-slug: stoppointidcrowdingline-get
      parameters:
      - in: query
        name: direction
        description: The direction of travel
      - in: path
        name: id
        description: The Naptan id of the stop
      - in: path
        name: line
        description: A particular line e
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Crowding
      - Line
  /StopPoint/{id}/DirectionTo/{toStopPointId}:
    get:
      summary: Stop Point  Direction To to Stop Point Id
      description: Returns the canonical direction, "inbound" or "outbound", for a
        given pair of stop point ids in the direction from -&gt; to..
      operationId: StopPoint_Direction
      x-api-path-slug: stoppointiddirectiontotostoppointid-get
      parameters:
      - in: path
        name: id
        description: Originating stop id (station naptan code e
      - in: query
        name: lineId
        description: Optional line id filter e
      - in: path
        name: toStopPointId
        description: Destination stop id (station naptan code e
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Direction
      - To
      - Stop
      - Point
      - Id
  /StopPoint/{id}/Route:
    get:
      summary: Stop Point  Route
      description: Returns the route sections for all the lines that service the given
        stop point ids.
      operationId: StopPoint_Route
      x-api-path-slug: stoppointidroute-get
      parameters:
      - in: path
        name: id
        description: A stop point id (station naptan codes e
      - in: query
        name: serviceTypes
        description: A comma-separated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Route
  /StopPoint/{id}/placeTypes:
    get:
      summary: Stop Point place Types
      description: Get a list of places corresponding to a given id and place types..
      operationId: StopPoint.id.placeTypes.get
      x-api-path-slug: stoppointidplacetypes-get
      parameters:
      - in: path
        name: id
        description: A naptan id for a stop point (station naptan code e
      - in: query
        name: placeTypes
        description: A comcomma-separated value representing the place types
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - Place
      - Types
  /StopPoint/{stopPointId}/CarParks:
    get:
      summary: Stop Point stop Point Id  Car Parks
      description: Get car parks corresponding to the given stop point id..
      operationId: StopPoint_GetCarParksById
      x-api-path-slug: stoppointstoppointidcarparks-get
      parameters:
      - in: path
        name: stopPointId
        description: stopPointId is required to get the car parks
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - Stop
      - Point
      - Id
      - ""
      - Car
      - Parks
  /StopPoint/{stopPointId}/TaxiRanks:
    get:
      summary: Stop Point stop Point Id  Taxi Ranks
      description: Gets a list of taxi ranks corresponding to the given stop point
        id..
      operationId: StopPoint_GetTaxiRanksByIds
      x-api-path-slug: stoppointstoppointidtaxiranks-get
      parameters:
      - in: path
        name: stopPointId
        description: stopPointId is required to get the taxi ranks
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - Stop
      - Point
      - Id
      - ""
      - Taxi
      - Ranks
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---