---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Get Shoppers Me Products Point Of Promotions Popid
    Offers
  description: Get shoppers me products point of promotions popid offers.
  version: v1
host: store.digitalriver.com
basePath: /store/{mysite}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/shoppers/me/carts/active/point-of-promotions/{id}/offers:
    get:
      summary: Get Shoppers Me Carts Active Point Of Promotions Offers
      description: Get shoppers me carts active point of promotions offers.
      operationId: getV1ShoppersMeCartsActivePointOfPromotionsOffers
      x-api-path-slug: v1shoppersmecartsactivepointofpromotionsidoffers-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Point
      - Promotions
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers
      description: Get shoppers me point of promotions offers.
      operationId: getV1ShoppersMePointOfPromotionsOffers
      x-api-path-slug: v1shoppersmepointofpromotionsidoffers-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid
      description: Get shoppers me point of promotions offers offerid.
      operationId: getV1ShoppersMePointOfPromotionsOffersOffer
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers
      description: Get shoppers me point of promotions offers offerid product offers.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffers
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers/{productId}:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers Productid
      description: Get shoppers me point of promotions offers offerid product offers
        productid.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffersProduct
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffersproductid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      - in: path
        name: productId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
      - Productid
  /v1/shoppers/me/products/{id}/point-of-promotions/{popId}/offers:
    get:
      summary: Get Shoppers Me Products Point Of Promotions Popid Offers
      description: Get shoppers me products point of promotions popid offers.
      operationId: getV1ShoppersMeProductsPointOfPromotionsPopOffers
      x-api-path-slug: v1shoppersmeproductsidpointofpromotionspopidoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: popId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
      - Point
      - Promotions
      - Popid
      - Offers
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