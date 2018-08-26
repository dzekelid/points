{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me Products Point Of Promotions Popid Offers",
    "_postman_id": "fbbfbe9b-964a-4077-9620-67e11d84b1d0",
    "description": "Get shoppers me products point of promotions popid offers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "1161d3d4-fcbe-4dd9-8816-de9d4f74b625",
          "name": "getOauth20Authorize",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/authorize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get oauth20 authorize."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a7c1f6a-1861-4aa9-b0d5-611b11cf95f9"
            }
          ]
        },
        {
          "id": "e29874c3-4c48-49b7-bea8-ebcb315b7b64",
          "name": "postOauth20Token",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/token",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post oauth20 token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7439bf99-a51f-49ba-9582-90f3ce5e6a5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "4de79e5d-f96e-4151-a28f-c81a73ed73b7",
          "name": "postV1Shoppers",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ad2a42c-265b-4eed-8e1a-bd92da3e157f"
            }
          ]
        },
        {
          "id": "c5133483-ade5-42ac-88cf-50773d1f55c8",
          "name": "getV1ShoppersApi",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers-api",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1623a51-81f8-43de-acb8-9824729dc9aa"
            }
          ]
        },
        {
          "id": "75acb85f-4747-4024-a9e8-df8c5452545e",
          "name": "getV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "278043bd-04ff-4c6c-b8d3-cefd556fb1f3"
            }
          ]
        },
        {
          "id": "422a4590-a525-4902-8276-0e30add4ecb3",
          "name": "postV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a20e22d5-4cf1-42a0-ac74-338926a0f161"
            }
          ]
        },
        {
          "id": "f0d63374-2617-4e64-ba48-39039d890b2f",
          "name": "getV1ShoppersMeAccount",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/account",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "405e99d8-6dd9-4413-91de-8a19d3288bb7"
            }
          ]
        },
        {
          "id": "8c18926c-1f26-4df6-afc2-f50c4766230c",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/addresses",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffec5e09-25a8-4a41-a911-4f3327c73471"
            }
          ]
        },
        {
          "id": "bfe87e52-b134-4d12-9167-7a4356eb95bf",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/addresses/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ede906d5-4c27-41ea-bf4c-6121c2385324"
            }
          ]
        },
        {
          "id": "fcc2c827-4cf3-4c6a-b52d-f53b39b26e1d",
          "name": "getV1ShoppersMeCartsActive",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c61af8a-8259-4d0f-9473-b8e2e38e4420"
            }
          ]
        },
        {
          "id": "c8fc14b1-1fa4-493b-8dba-58cfe9ff1213",
          "name": "postV1ShoppersMeCartsActive",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bab00e34-0283-49cb-bc82-c09ddee389e4"
            }
          ]
        },
        {
          "id": "a0db8bc8-0121-4ce5-be7a-cd4fa58476f3",
          "name": "postV1ShoppersMeCartsActiveApplyShippingOption",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/apply-shipping-option",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active apply shipping option."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0799dee6-65eb-43f6-afa3-dc6c35fb75ae"
            }
          ]
        },
        {
          "id": "459bc2e1-ca76-4115-a801-2fe39fdae485",
          "name": "postV1ShoppersMeCartsActiveApplyShopper",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/apply-shopper",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active apply shopper."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b33ead55-684f-4a3c-ba47-9922ddb3e142"
            }
          ]
        },
        {
          "id": "693b4fcc-44b6-4fba-a097-97a67c2e299b",
          "name": "getV1ShoppersMeCartsActiveBillingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/billing-address",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce453e33-3cfd-436a-831c-03e199c68ee4"
            }
          ]
        },
        {
          "id": "0bc184d0-e8a3-4d2f-8f13-b8642b36fbd9",
          "name": "putV1ShoppersMeCartsActiveBillingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/billing-address",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put shoppers me carts active billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8746b64c-7b6c-446b-8b58-0b0fd1fa9a3e"
            }
          ]
        },
        {
          "id": "8f89aed7-f1b2-4570-88f3-b6a8028a27ec",
          "name": "getV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93e95d2a-3ef6-47f6-a29a-2496555d287e"
            }
          ]
        },
        {
          "id": "f96c523b-a26f-42e9-93e6-74dd9c0041bb",
          "name": "postV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7599256f-3681-4e86-b5cd-cbcd0a0d7234"
            }
          ]
        },
        {
          "id": "8d30ee97-3eee-4cbe-a733-b62ea37e8ae5",
          "name": "deleteV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c46d142f-2fab-48b6-b9a4-cb24788d7312"
            }
          ]
        },
        {
          "id": "404613f8-1bbb-46b3-b2ca-c81215efb2ec",
          "name": "getV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9dd985f-e556-4e81-873d-c9b8749d120c"
            }
          ]
        },
        {
          "id": "01d0d9f0-bbcb-4fa6-8e9b-308f9de07109",
          "name": "postV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4eb8680-5c8c-4ad2-818a-63e2ffaa0deb"
            }
          ]
        },
        {
          "id": "95b8ed10-735b-495c-a83d-08397e37246c",
          "name": "deleteV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bee676f4-982c-4c53-8dd4-2c1ecc17393a"
            }
          ]
        },
        {
          "id": "73b2e661-2d69-46cd-acd7-966f98e44c25",
          "name": "getV1ShoppersMeCartsActivePointOfPromotionsOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/point-of-promotions/:id/offers"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active point of promotions offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b295d561-75c1-447e-93cf-b7366158d5d3"
            }
          ]
        },
        {
          "id": "34f3baab-e185-48ed-a0d6-91ebc7e86a6e",
          "name": "getV1ShoppersMeCartsActiveShippingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-address",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9eb7120f-0776-4cb0-9230-c50f0d02c919"
            }
          ]
        },
        {
          "id": "822b5a5a-705c-4ef6-912e-bcc003032de2",
          "name": "putV1ShoppersMeCartsActiveShippingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-address",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put shoppers me carts active shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b1b343a-090b-4948-81ea-718304720a86"
            }
          ]
        },
        {
          "id": "4aaa7a15-84dc-448e-a501-3562fc42bb44",
          "name": "getV1ShoppersMeCartsActiveShippingOptions",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-options",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b04f4b33-04c2-4ec9-bc07-4d7f69bba249"
            }
          ]
        },
        {
          "id": "bbda3cd6-93bb-425c-be96-c92074f725bc",
          "name": "getV1ShoppersMeCartsActiveShippingOptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/shipping-options/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "849caedc-44bd-49e5-9f2e-654b55e76bf0"
            }
          ]
        },
        {
          "id": "38b2821f-dd07-4326-aa9b-812dd84f17ff",
          "name": "postV1ShoppersMeCartsActiveSubmitCart",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/submit-cart",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active submit cart."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9205cb2e-1533-4b03-a915-a445b09f725c"
            }
          ]
        },
        {
          "id": "409998c7-8124-4916-8ebf-aab31425f9a0",
          "name": "getV1ShoppersMeCartsActiveWebCheckout",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/web-checkout",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active web checkout."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0a46002-68cf-44ce-aceb-9dff0ee87e5f"
            }
          ]
        },
        {
          "id": "d325623b-17d5-453c-b4d4-2d2f29412831",
          "name": "postV1ShoppersMeCartsActiveWebCheckout",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/web-checkout",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active web checkout."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62e49702-32cd-4f95-8a50-5302ca19525d"
            }
          ]
        },
        {
          "id": "cc38f5d1-ac91-41a9-a5b6-d1c2c2433c2c",
          "name": "getV1ShoppersMeCategories",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/categories",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb6acc42-9443-4338-b648-a6d6af6e46fb"
            }
          ]
        },
        {
          "id": "3b5d2c60-4dfc-4679-9911-395923ea75f4",
          "name": "getV1ShoppersMeCategories",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/categories/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "525dfd66-885a-4891-9f88-8073e90c7a46"
            }
          ]
        },
        {
          "id": "2533a1f8-858c-4e7a-b012-9d876968d963",
          "name": "getV1ShoppersMeCategoriesProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/categories/:id/products"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76fadcb7-ddb0-47c6-9d13-724e68c378bd"
            }
          ]
        },
        {
          "id": "3e8c89a8-d5fb-4f62-a353-be66a8bfa54b",
          "name": "getV1ShoppersMeOrders",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/orders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1afaa6ea-4462-4ba0-9abc-4bcef2a8e41b"
            }
          ]
        },
        {
          "id": "c84a683d-cda7-4fb1-a6c9-9a40d132f684",
          "name": "postV1ShoppersMeOrders",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/orders",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea70cbee-5c5b-459f-bacd-cf23f08b7d16"
            }
          ]
        },
        {
          "id": "f04b0ef3-98be-4dca-8580-cfc1c3dfa707",
          "name": "getV1ShoppersMeOrders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d15f8128-7c31-422b-af83-f814eeb4cd46"
            }
          ]
        },
        {
          "id": "131ae4e4-cec7-4193-aa09-db72a035d680",
          "name": "getV1ShoppersMeOrdersBillingAddress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/billing-address"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91b17d84-c6ac-488d-a488-1a51b7bcf7d9"
            }
          ]
        },
        {
          "id": "d319ac3c-91ac-4378-8390-2cd03e223d73",
          "name": "getV1ShoppersMeOrdersLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/line-items"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff6e70f6-62b7-47a5-90f6-d287079d2c09"
            }
          ]
        },
        {
          "id": "3f6366a1-79ea-4829-8e04-7f44682e66f1",
          "name": "getV1ShoppersMeOrdersLineItemsLineitem",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/line-items/:lineItemId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lineItemId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders line items lineitemid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96daea31-3a3e-402c-8a98-c2cf7f43ee43"
            }
          ]
        },
        {
          "id": "c807139e-8d0e-4057-8055-e7f0ec77f998",
          "name": "getV1ShoppersMeOrdersShippingAddress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/shipping-address"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb32f84c-9a98-4f3e-9cc5-e3be21086bba"
            }
          ]
        },
        {
          "id": "454cd92b-a244-45fc-9327-0f9552be743a",
          "name": "getV1ShoppersMePaymentOptions",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/payment-options",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me payment options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cd48d94-a864-4395-80bc-c789a9a968f6"
            }
          ]
        },
        {
          "id": "b36ab53c-ff8b-4fc6-82f2-6bdaf0c51d87",
          "name": "getV1ShoppersMePaymentOptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/payment-options/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me payment options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e70e7b9-2015-4bd4-88e7-b30d3686265a"
            }
          ]
        },
        {
          "id": "f84653e8-5213-47a1-afe6-29ee73fa7afd",
          "name": "getV1ShoppersMePointOfPromotionsOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aabb5260-8cf4-47a9-ab24-1f822eb49d22"
            }
          ]
        },
        {
          "id": "ef3fd5dd-5822-47b4-bac9-ac2407d4e4b3",
          "name": "getV1ShoppersMePointOfPromotionsOffersOffer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4bd5c23d-5707-42e8-bb6b-4b315f7c275d"
            }
          ]
        },
        {
          "id": "e15aa85a-199d-4288-a8ef-78511788d204",
          "name": "getV1ShoppersMePointOfPromotionsOffersOfferProductOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId/product-offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid product offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef77f94a-7776-4e5c-8a59-6fbdd1ea1f2a"
            }
          ]
        },
        {
          "id": "e2d2889a-38ef-4f27-8998-4bea3ae715b5",
          "name": "getV1ShoppersMePointOfPromotionsOffersOfferProductOffersProduct",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId/product-offers/:productId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid product offers productid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d39479e8-3030-4856-9fe2-b19af3e761bf"
            }
          ]
        },
        {
          "id": "e3770275-507d-46af-a580-969832e65a02",
          "name": "getV1ShoppersMeProductSearch",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/product-search",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me product search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdee5fde-4335-458b-bbe5-6f1dee538ff9"
            }
          ]
        },
        {
          "id": "2bf320a4-8b8c-4f9e-a17e-d020cc150378",
          "name": "getV1ShoppersMeProducts",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/products",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5da74ed1-d988-4238-b0e3-d8c60077febc"
            }
          ]
        },
        {
          "id": "1fb447eb-7c6c-415c-9e65-a41c90adefcd",
          "name": "getV1ShoppersMeProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/products/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8ceacfe-d669-4bab-8dc3-0d64afc5359a"
            }
          ]
        },
        {
          "id": "f9be61c5-146b-410a-a30b-71ffd2733739",
          "name": "getV1ShoppersMeProductsPointOfPromotionsPopOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/products/:id/point-of-promotions/:popId/offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "popId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products point of promotions popid offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ddd6c92-b924-405e-b03b-199c8db77c09"
            }
          ]
        }
      ]
    }
  ]
}