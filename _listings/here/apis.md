---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Points
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Map Tile API - Filtering Points of Interest
  x-api-slug: maptilenewestnormal-day161874325072256png8-get
  description: "*Request a map tile including selected points of interest*\n\nPoints
    of interest are displayed by passing the `pois` parameter in the request URL.
    The type of points of interest to be displayed can be filtered by using a hexadecimal
    bitmask.\n  \n\n\n\n* **pois**  `text`\n \\- Displays points of interest if present
    \ \n\n Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`,
    `mini`\n\n* **app_id**  `text`\n \\- A 20 byte Base64 URL-safe encoded string
    used for the authentication of the client application.    You must include an
    `app_id` with every request.\n\n* **app_code**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/maptilenewestnormal-day161874325072256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/maptilenewestnormal-day161874325072256png8-get-openapi.md
- name: Map Tile API - Point of Interest Categories
  x-api-slug: metapois-get
  description: "*Request point of interest category information*\n\nTo make a request
    for point-of-interest information, use `meta/pois` in the path of the request
    URL.\n  \n\n\n\n* **output**  `enum`\n \\- A 20 byte Base64 URL-safe encoded string
    used for the authentication of the client application.    You must include an
    `app_id` with every request.\n\n Valid values are : `json`, `text`\n\n* **app_id**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_id` with every request..
    \ \n\n* **app_code**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used
    for the authentication of the client application.    You must include an `app_code`
    with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/metapois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/metapois-get-openapi.md
- name: Map Tile API - Point of Interest Categories
  x-api-slug: metapois-get
  description: "*Request point of interest category information*\n\nTo make a request
    for point-of-interest information, use `meta/pois` in the path of the request
    URL.\n  \n\n\n\n* **output**  `enum`\n \\- A 20 byte Base64 URL-safe encoded string
    used for the authentication of the client application.    You must include an
    `app_id` with every request.\n\n Valid values are : `json`, `text`\n\n* **app_id**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_id` with every request..
    \ \n\n* **app_code**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used
    for the authentication of the client application.    You must include an `app_code`
    with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/metapois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/points/master/_listings/here/metapois-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---