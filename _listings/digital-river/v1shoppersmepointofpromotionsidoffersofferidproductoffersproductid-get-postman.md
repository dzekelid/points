{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me Point Of Promotions Offers Offerid Product Offers Productid",
    "_postman_id": "ca395980-38e0-4625-bb48-216be1740ff1",
    "description": "Get shoppers me point of promotions offers offerid product offers productid.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "cbe6e8db-6fa7-4d97-9a5b-5bbbc1c30feb",
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
              "id": "37e7c1a2-e16d-4791-8d14-75a9538f810f"
            }
          ]
        },
        {
          "id": "1fdf50a0-0f1b-46c7-b201-de43a7004b29",
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
              "id": "43ad933b-ca30-44a3-a58d-ec09e7164f41"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "e3e90d10-107f-46f4-9f79-96960aacb97c",
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
              "id": "9d49b377-bf9d-4641-8749-f7924aec110f"
            }
          ]
        },
        {
          "id": "059cde28-d6a7-44cb-a8d8-636151562f7b",
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
              "id": "3f94f96c-2cb3-44a0-845a-735c4293cb4f"
            }
          ]
        },
        {
          "id": "9ee8c610-91a5-4a2e-a4d1-ab2e07ee67d5",
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
              "id": "c27dfdf6-ad2c-46dc-900a-a3b9e922577a"
            }
          ]
        },
        {
          "id": "3f032d2c-75e2-402c-b472-5561eaa12e07",
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
              "id": "3837acbc-f57d-458b-a617-c7e435074d9a"
            }
          ]
        },
        {
          "id": "0bfbbd3d-6aa9-4f55-b847-4c7fca7f659c",
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
              "id": "80b4db03-072b-4749-a006-ed9f7d204ade"
            }
          ]
        },
        {
          "id": "186d0eed-b1b9-48ec-b149-d8a32ab8db59",
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
              "id": "9d2ecc24-6360-4161-8561-2a3af9ba0977"
            }
          ]
        },
        {
          "id": "93c5a4fe-b51b-4d7e-a617-4a95d22e2240",
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
              "id": "1476aa44-7e73-4524-842e-17b440138819"
            }
          ]
        },
        {
          "id": "d86f4b75-3dea-4609-bf2e-aaf283b55b54",
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
              "id": "07f3b242-4d24-4296-9220-e61ae2ff4626"
            }
          ]
        },
        {
          "id": "91f16d97-2d00-400a-8bf6-b6db30650022",
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
              "id": "1f8af287-15ee-42fe-b906-0d1e58500a66"
            }
          ]
        },
        {
          "id": "741f1dcd-3fff-4b88-be95-984600f7ead9",
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
              "id": "b16a0969-366e-46e9-bedc-0f6362f084e0"
            }
          ]
        },
        {
          "id": "5f296510-e380-437d-b69e-5a64192ddb9b",
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
              "id": "9ef4dfbb-bbf7-4fdc-b2f6-5f94e2b1d9cc"
            }
          ]
        },
        {
          "id": "4cf4fb22-8d54-4dc2-b626-3d40aa745979",
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
              "id": "8db0192f-92d2-4e86-b6c8-9c1d0d7fc260"
            }
          ]
        },
        {
          "id": "e516817d-36f2-4ff1-a251-7be7f651c3ab",
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
              "id": "e6736863-174b-412c-88ea-71bd157917e1"
            }
          ]
        },
        {
          "id": "3e0ceeaf-511e-4263-a1d7-1661db242f8d",
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
              "id": "0380dfca-2a24-49e8-917a-f88c2b745cb5"
            }
          ]
        },
        {
          "id": "b14ae6e9-83c4-4bba-8697-2709e58f4e04",
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
              "id": "5868f116-2151-4717-b138-e4e7f3358a72"
            }
          ]
        },
        {
          "id": "a4f0bb8c-ce72-4a16-ae27-25cfd239f0c8",
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
              "id": "f3087e4d-433b-472a-b29a-bc39cb8592ab"
            }
          ]
        },
        {
          "id": "85c843d7-01df-47fc-8be0-7845ab02a520",
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
              "id": "57486b75-9ef2-4caa-aa54-da5ba52efd7e"
            }
          ]
        },
        {
          "id": "6b42c819-cb28-49db-b639-fb00e1ca7040",
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
              "id": "4c8748e2-dd46-49b3-a102-eae312aecfff"
            }
          ]
        },
        {
          "id": "4f15101b-51b3-4d80-be0c-84867b2ed0c1",
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
              "id": "9e24051d-11be-4d44-b957-4ff0936b0a8d"
            }
          ]
        },
        {
          "id": "fd3a32ac-67ad-48ae-9d4d-ac3f4c5f2826",
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
              "id": "04681a4a-3a65-4e45-996d-4707d0a653cd"
            }
          ]
        },
        {
          "id": "1fe31f7f-0d51-4352-ac1b-d9656c5cdb30",
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
              "id": "ada6f2d0-9282-4ea2-a61b-e570e090796b"
            }
          ]
        },
        {
          "id": "43d358f8-e3cd-4e3d-835a-9d9ae6c8d2fc",
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
              "id": "4f745dab-f9b1-4af4-adcc-4866dc66aa9a"
            }
          ]
        },
        {
          "id": "bcccd1b0-f2a9-4515-83b2-c134e4365c12",
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
              "id": "e83f6dea-371c-4b41-a390-6f305b66afcc"
            }
          ]
        },
        {
          "id": "0fdaa4d8-7690-4ce2-a857-7e2d9275c6aa",
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
              "id": "fe30d007-72be-4788-aee8-5d830a64ed62"
            }
          ]
        },
        {
          "id": "c68c184e-228b-4697-ab77-4c384ceb44aa",
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
              "id": "3c17536b-56e7-4d95-9c7b-18fb45fe7b81"
            }
          ]
        },
        {
          "id": "37937d41-c0e4-4b03-ab41-9167ff2e78e3",
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
              "id": "da6748f7-9327-4d78-8e9a-b9615cb830c8"
            }
          ]
        },
        {
          "id": "f5a0b246-eaaa-4d41-bc78-090fa7e7afb5",
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
              "id": "044b7045-3e60-42d8-b18a-ab001baf3090"
            }
          ]
        },
        {
          "id": "8e570400-99d2-488d-91d0-5b495f117e76",
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
              "id": "1ad5c959-3f87-49d6-9d0d-4d5c52ba06ea"
            }
          ]
        },
        {
          "id": "ff63bc37-fad5-412f-861a-480f377189cd",
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
              "id": "bcb8e468-6b4b-4121-8c1a-6ecf3981b978"
            }
          ]
        },
        {
          "id": "cf09df03-091c-411d-9f37-e3c19c5305ee",
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
              "id": "e0bcae60-4a48-4052-b694-142138a2df79"
            }
          ]
        },
        {
          "id": "4e60073d-42c5-430e-b627-ef9256b1d36c",
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
              "id": "7cca74a3-d175-4a22-9eb7-3a612aa620ee"
            }
          ]
        },
        {
          "id": "2cd68fff-4f56-4792-b41c-461ec54f28c3",
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
              "id": "4a81b751-b21d-4d56-b078-61ced88c6684"
            }
          ]
        },
        {
          "id": "a69e0039-3542-423d-8dcf-06e8c9ace96a",
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
              "id": "d8fdc8cd-bee8-413e-9781-f111eabe4cc3"
            }
          ]
        },
        {
          "id": "98eaa231-bbe1-4de7-bb09-4d48360b88f4",
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
              "id": "b129d4b6-6990-4158-a789-b02da9170f86"
            }
          ]
        },
        {
          "id": "89494772-f1e2-416e-9c9d-957a80603285",
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
              "id": "8dec34bc-2f89-4df5-bc88-535d5b076650"
            }
          ]
        },
        {
          "id": "e0bd0ca8-f2e3-4200-9aa3-ada988765585",
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
              "id": "d06a5623-cfab-44a1-9de6-09ff49ea873a"
            }
          ]
        },
        {
          "id": "3b201a31-2715-4d8d-9bfe-f411e8078791",
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
              "id": "0361c904-e9ed-4a04-a52f-169a7b1a934e"
            }
          ]
        },
        {
          "id": "10b1f36d-84ca-42c5-a584-455d41264cad",
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
              "id": "13908807-345d-4417-a55e-00d4ab434a88"
            }
          ]
        },
        {
          "id": "77a992a3-fd56-4f77-8383-eaaf40fcf516",
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
              "id": "0d0b4515-5af7-47c2-b477-c419a44c02a8"
            }
          ]
        },
        {
          "id": "95f43473-e0e6-4467-8a19-310c873c02a7",
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
              "id": "e2059a68-ca53-48ff-bf3a-e00443d54af5"
            }
          ]
        },
        {
          "id": "fa7c6902-2038-4b17-a3ae-6cb795d72a4c",
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
              "id": "020202cc-830c-4f44-9d86-3e5c8273dba6"
            }
          ]
        },
        {
          "id": "9a2b7d29-e4f8-4713-96ef-b8683980f6f4",
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
              "id": "26eaf324-a0a1-42d2-ad11-6b4d6c1bd0bd"
            }
          ]
        },
        {
          "id": "5855a020-b2b0-46e8-8af5-98fdefe6ee16",
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
              "id": "2f2a22b8-9046-43cd-aa32-b5e4efc49caa"
            }
          ]
        }
      ]
    }
  ]
}