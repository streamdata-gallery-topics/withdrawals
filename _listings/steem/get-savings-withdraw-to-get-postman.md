{
  "info": {
    "name": "Steem get_savings_withdraw_to",
    "_postman_id": "97fab1e9-ed65-4c11-9653-c03fbdae02b8",
    "description": "get_savings_withdraw_to",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "5a087a43-6c9e-42b1-8083-1a3d8d0d3588",
          "name": "returns-version-information-of-connected-steem-nodewebsocket",
          "request": {
            "url": "http://api.steemjs.com/get_version",
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
            "description": "Returns version information of connected Steem node/websocket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7b879e0-d7ab-4b32-9be8-01c888d1b48f"
            }
          ]
        },
        {
          "id": "3df53b34-390a-4cf4-b365-5e247fb83e62",
          "name": "get-chain-properties",
          "request": {
            "url": "http://api.steemjs.com/get_chain_properties",
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
            "description": "get chain properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "977d9d89-f029-4107-9a1b-7a0ff2df5e42"
            }
          ]
        },
        {
          "id": "09a5090e-47a5-4f3f-a3c6-948fcc3e1894",
          "name": "get-config",
          "request": {
            "url": "http://api.steemjs.com/get_config",
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
            "description": "get config"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f9f0dc7-6835-4717-b6cc-1fa7f50eef50"
            }
          ]
        },
        {
          "id": "497f3f8a-6e13-4b78-8bfa-5246c7481875",
          "name": "get-dynamic-global-properties",
          "request": {
            "url": "http://api.steemjs.com/get_dynamic_global_properties",
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
            "description": "get_dynamic_global_properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "098cb24a-2acd-4fce-8535-a6f1fcd1ba65"
            }
          ]
        },
        {
          "id": "af51e261-73d4-4bbc-93dd-7d1b6c3504f3",
          "name": "get-feed-history",
          "request": {
            "url": "http://api.steemjs.com/get_feed_history",
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
            "description": "get_feed_history"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9060a647-6646-4358-a4f7-8d2f38c48b75"
            }
          ]
        },
        {
          "id": "52ac5397-9d42-4676-a656-7ec1d3db1f84",
          "name": "get-current-median-history-price",
          "request": {
            "url": "http://api.steemjs.com/get_current_median_history_price",
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
            "description": "get_current_median_history_price"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11de404b-7a7f-4c80-a521-0021879ba109"
            }
          ]
        },
        {
          "id": "280929d1-a5de-4f78-9e47-cfa1ee513238",
          "name": "get-hardfork-version",
          "request": {
            "url": "http://api.steemjs.com/get_hardfork_version",
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
            "description": "get_hardfork_version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2e1bbf8-58be-4443-9e77-c71fea560b28"
            }
          ]
        },
        {
          "id": "3183469d-b888-49cd-8e33-ad3f1300a40e",
          "name": "get-next-scheduled-hardfork",
          "request": {
            "url": "http://api.steemjs.com/get_next_scheduled_hardfork",
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
            "description": "get_next_scheduled_hardfork"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd6ab54a-23d7-47b3-8bf6-9b60916ae960"
            }
          ]
        },
        {
          "id": "4e085412-5801-4acc-87a9-6de8dce6a2a7",
          "name": "get-witness-count",
          "request": {
            "url": "http://api.steemjs.com/get_witness_count",
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
            "description": "get_witness_count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6c1b527-f9ce-4f90-a3bd-79cce69ca56e"
            }
          ]
        },
        {
          "id": "69d5bb7f-324a-4844-8839-63d4c7ecfd22",
          "name": "get-witness-schedule",
          "request": {
            "url": "http://api.steemjs.com/get_witness_schedule",
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
            "description": "get_witness_schedule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9323b1ff-20f0-4042-9aea-f97249639ffd"
            }
          ]
        },
        {
          "id": "7d2aeb9a-81f7-43e2-ac07-572afd6336cb",
          "name": "get-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses?witnessIds=%7B%7D",
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
            "description": "get_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc37598b-feb2-47c4-bd81-137a4e104ab8"
            }
          ]
        },
        {
          "id": "2df670b6-1a1f-4521-a72b-d31b0167f2a9",
          "name": "get-witness-by-account",
          "request": {
            "url": "http://api.steemjs.com/get_witness_by_account?accountName=%7B%7D",
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
            "description": "get_witness_by_account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d635a3e-84d9-4c45-b77c-6a9426d73e2f"
            }
          ]
        },
        {
          "id": "c90750fe-c551-4395-98eb-38d7218fc2e8",
          "name": "get-witnesses-by-vote",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses_by_vote?from=%7B%7D&limit=%7B%7D",
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
            "description": "get_witnesses_by_vote"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af005e09-b411-4f9a-8379-61ba835e43f1"
            }
          ]
        },
        {
          "id": "6c346a9a-b43f-4610-b918-7e733c9b60cc",
          "name": "get-active-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_active_witnesses",
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
            "description": "get_active_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3df90dc6-6be5-40d7-b2b5-3656de7be57c"
            }
          ]
        },
        {
          "id": "0a8677aa-f4fe-4c62-be71-fee795d21f0d",
          "name": "get-miner-queue",
          "request": {
            "url": "http://api.steemjs.com/get_miner_queue",
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
            "description": "get_miner_queue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5ea5b85-96ec-48d9-b416-e3c395809d14"
            }
          ]
        },
        {
          "id": "cbcd13cc-79ab-40e3-b8ae-910e4c6a8baa",
          "name": "get-liquidity-queue",
          "request": {
            "url": "http://api.steemjs.com/get_liquidity_queue?limit=%7B%7D&startAccount=%7B%7D",
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
            "description": "get_liquidity_queue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "963f3984-6592-49d2-a46d-3989d4774445"
            }
          ]
        },
        {
          "id": "a119c5cd-df6f-4cd7-8c37-e4adfc82cf44",
          "name": "get-open-orders",
          "request": {
            "url": "http://api.steemjs.com/get_open_orders?owner=%7B%7D",
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
            "description": "get_open_orders"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a61c8761-2d23-4823-952b-79438dba9956"
            }
          ]
        },
        {
          "id": "12b4f921-2511-4187-bfd8-fcc376097055",
          "name": "get-order-book",
          "request": {
            "url": "http://api.steemjs.com/get_order_book?limit=%7B%7D",
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
            "description": "get_order_book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07076afa-fe2d-449e-97e9-583b2bf35a9f"
            }
          ]
        },
        {
          "id": "08afa3fb-e26c-4b90-9580-5540719e086c",
          "name": "get-tags",
          "request": {
            "url": "http://api.steemjs.com/get_active_categories?after=%7B%7D&limit=%7B%7D",
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
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d488bb6-05a7-49a2-bc71-d9c784bf9400"
            }
          ]
        },
        {
          "id": "d4a1f34c-f88e-482f-a178-ad4ed2350657",
          "name": "get-tags1",
          "request": {
            "url": "http://api.steemjs.com/get_best_categories?after=%7B%7D&limit=%7B%7D",
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
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbc9ee66-2eee-4e9e-94eb-5ff8563a9240"
            }
          ]
        },
        {
          "id": "56e7138d-2848-4585-9025-a1709c307e07",
          "name": "get-tags2",
          "request": {
            "url": "http://api.steemjs.com/get_recent_categories?after=%7B%7D&limit=%7B%7D",
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
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e02d17d5-69e3-4cae-8925-bad731ae90e4"
            }
          ]
        },
        {
          "id": "21cdbe74-cea4-4672-8b7e-661ffb8815fb",
          "name": "get-tags3",
          "request": {
            "url": "http://api.steemjs.com/get_trending_categories?after=%7B%7D&limit=%7B%7D",
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
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a11782d-ec53-4221-9146-ddb7e23cb79f"
            }
          ]
        },
        {
          "id": "67dfa7ee-8e66-42d6-8dd5-67905ef0a865",
          "name": "get-tags",
          "request": {
            "url": "http://api.steemjs.com/get_trending_tags?afterTag=%7B%7D&limit=%7B%7D",
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
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6673509-1189-44b6-ab3b-cfbef4ae7ead"
            }
          ]
        },
        {
          "id": "82ce0104-354e-4003-b88f-36dc3cdb79b8",
          "name": "get-content",
          "request": {
            "url": "http://api.steemjs.com/get_content?author=%7B%7D&permlink=%7B%7D",
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
            "description": "get content"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20e5f285-47e3-4fb9-a81b-bdb7d29ff256"
            }
          ]
        },
        {
          "id": "c5830563-4a22-437b-a6e3-b20c492c6412",
          "name": "get-content-replies",
          "request": {
            "url": "http://api.steemjs.com/get_content_replies?author=%7B%7D&permlink=%7B%7D",
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
            "description": "get content replies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35f410e8-bcbb-4feb-a509-d28e272057b0"
            }
          ]
        },
        {
          "id": "c15fa609-0e0f-492e-a621-398d3097480b",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_trending?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc86f5fa-efb0-44df-9e72-efd1b3eb22fc"
            }
          ]
        },
        {
          "id": "2c7adc18-b6fa-409b-b447-158b23831e3d",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio1",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_trending30?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30717161-4e0e-44d2-a623-5ad9fc9ba2ba"
            }
          ]
        },
        {
          "id": "2adcb167-6001-4f60-b282-4c25ccd95950",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio2",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_created?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e06e9e9a-82be-4b12-80be-3197fb639b0b"
            }
          ]
        },
        {
          "id": "64cb646c-fab2-44c5-bfb0-a8eab82b59a3",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio3",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_active?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1de65d21-e395-494d-a67c-1c320e6a850d"
            }
          ]
        },
        {
          "id": "8f1a6564-66d2-40d9-ad85-5b8e0efc2f8e",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio4",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_promoted?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78578268-dfa6-4ead-b21f-0b9ff485a16a"
            }
          ]
        },
        {
          "id": "1cba0072-8aa5-4fcd-b232-f1ad9d611c1e",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio5",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_cashout?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a791db8f-5563-48dc-8104-0f5e053c6c74"
            }
          ]
        },
        {
          "id": "ff29f37e-0924-4b72-8fe9-78b74ae00025",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio6",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_payout?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "660a881d-3d31-4fb8-b5e3-b7f2f772c18c"
            }
          ]
        },
        {
          "id": "b94da5c5-3992-465a-9eab-db776b282c1c",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio7",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_votes?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e7f8b45-4005-4b66-94fe-4fb6d1414e71"
            }
          ]
        },
        {
          "id": "6c137cb8-2e54-4052-a12f-ac9fb04bcc32",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio8",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_children?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33bb6e6c-d437-4978-ad47-83808c03f821"
            }
          ]
        },
        {
          "id": "ec14a90b-5898-42bb-8ef9-6186b614baf3",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio9",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_hot?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58ea21e6-5920-431f-a1e4-915c5e6eeaad"
            }
          ]
        },
        {
          "id": "625c01e4-05ba-4497-b793-7ea8c1dd71a4",
          "name": "get-discussions--query-example-limit10-tagsgoodkarma-or-start-authorauthor-permlinkpermlink-for-pagi",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_feed?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tags\":\"good-karma\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "723076e7-36d1-4841-b165-a26af27d7170"
            }
          ]
        },
        {
          "id": "797dc233-8c98-4ff7-abc1-15398c6238e3",
          "name": "get-discussions--query-example-limit10-taggoodkarma-or-start-authorauthor-permlinkpermlink-for-pagin",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_blog?query=%7B%7D",
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
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"good-karma\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b73493b3-28f0-4ce0-8e1e-274308659f84"
            }
          ]
        },
        {
          "id": "4acfc2bb-d007-4053-9605-c811d904c579",
          "name": "get-discussions--query-example-start-authorauthor-start-permlinkpermlink-limi10",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_comments?query=%7B%7D",
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
            "description": "get discussions, | query example {\"start_author\":\"author\", \"start_permlink\":\"permlink\", \"limi\":\"10\"}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe0ec2bf-3773-41f0-852b-7a6661f0bc4a"
            }
          ]
        },
        {
          "id": "688c94aa-8870-4d62-8ffb-8e97d895a8d1",
          "name": "get-discussions-by-author-before-date",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_author_before_date?author=%7B%7D&beforeDate=%7B%7D&limit=%7B%7D&startPermlink=%7B%7D",
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
            "description": "get_discussions_by_author_before_date"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f68169f-0089-4174-875b-ed5ce7aa4a11"
            }
          ]
        },
        {
          "id": "e96843cb-6d48-437c-863e-383bbc58b4a8",
          "name": "get-replies-by-last-update",
          "request": {
            "url": "http://api.steemjs.com/get_replies_by_last_update?limit=%7B%7D&startAuthor=%7B%7D&startPermlink=%7B%7D",
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
            "description": "get_replies_by_last_update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d151cf9-08d1-4c52-adb3-a5ce3f85e43e"
            }
          ]
        },
        {
          "id": "5628b051-5ce9-43cf-8d64-e1475541f190",
          "name": "get-state",
          "request": {
            "url": "http://api.steemjs.com/get_state?path=%7B%7D",
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
            "description": "get_state"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "510d4c42-2dd5-4f59-95da-85d9a03f2886"
            }
          ]
        },
        {
          "id": "bcfa1468-5240-4449-9de4-c1b9af6eed00",
          "name": "get-active-votes",
          "request": {
            "url": "http://api.steemjs.com/get_active_votes?author=%7B%7D&permlink=%7B%7D",
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
            "description": "get_active_votes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31c4a829-5323-4b16-9eb9-34467d14ccfd"
            }
          ]
        },
        {
          "id": "c237c2b2-5018-4a8a-bbd2-19ba432e60a3",
          "name": "get-account-votes",
          "request": {
            "url": "http://api.steemjs.com/get_account_votes?voter=%7B%7D",
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
            "description": "get_account_votes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c3c64a4-6299-4fda-a248-cc43abd93f07"
            }
          ]
        },
        {
          "id": "7bc86be1-3e65-4775-9fed-6487bf003822",
          "name": "get-owner-history",
          "request": {
            "url": "http://api.steemjs.com/get_owner_history?account=%7B%7D",
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
            "description": "get_owner_history"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e6e1891-692d-4c4e-9b05-ce33e16fdac5"
            }
          ]
        },
        {
          "id": "5e2565f9-fc46-410a-b7d7-85e05479826e",
          "name": "get-conversation-requests-of-account",
          "request": {
            "url": "http://api.steemjs.com/get_conversion_requests?accountName=%7B%7D",
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
            "description": "get conversation requests of account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30929a90-0686-43a7-8fdc-dd8bfb8027d9"
            }
          ]
        },
        {
          "id": "622bb6d8-d9e2-4b3b-bba3-7a7c5bcc0dbb",
          "name": "get-recovery-request",
          "request": {
            "url": "http://api.steemjs.com/get_recovery_request?account=%7B%7D",
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
            "description": "get_recovery_request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1bc4d5c-798e-47ea-a40c-51358271698b"
            }
          ]
        },
        {
          "id": "d8687019-ca93-4433-a4f0-b6bdb4cc016d",
          "name": "get-follow-count",
          "request": {
            "url": "http://api.steemjs.com/get_follow_count?account=%7B%7D",
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
            "description": "get_follow_count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14db6069-c222-4b54-aa7c-f097b07720eb"
            }
          ]
        },
        {
          "id": "2d6a30e0-7138-419b-84c3-bc0d97f726dc",
          "name": "get-followers",
          "request": {
            "url": "http://api.steemjs.com/get_followers?following=%7B%7D&followType=%7B%7D&limit=%7B%7D&startFollower=%7B%7D",
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
            "description": "get_followers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3b6e2f1-4c74-4f10-bc1f-f4a22e967e8b"
            }
          ]
        },
        {
          "id": "5f8efb78-d531-4545-8c2e-f033300780a8",
          "name": "get-following",
          "request": {
            "url": "http://api.steemjs.com/get_following?follower=%7B%7D&followType=%7B%7D&limit=%7B%7D&startFollowing=%7B%7D",
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
            "description": "get_following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30bb153a-6cd6-497f-8e60-620b26c2a137"
            }
          ]
        },
        {
          "id": "4649b539-a1f8-4cba-83c6-8536a19d5389",
          "name": "get-escrow",
          "request": {
            "url": "http://api.steemjs.com/get_escrow?escrowId=%7B%7D&from=%7B%7D",
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
            "description": "get_escrow"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3eab294-5abc-42c2-aa34-2e148e4f4092"
            }
          ]
        },
        {
          "id": "eb3be8c4-d150-47ed-9f65-028bca0d945f",
          "name": "get-withdraw-routes",
          "request": {
            "url": "http://api.steemjs.com/get_withdraw_routes?account=%7B%7D&withdrawRouteType=%7B%7D",
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
            "description": "get_withdraw_routes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf80ad4d-b9ec-4eda-af94-e778b863fc07"
            }
          ]
        },
        {
          "id": "bd3e643d-ac7b-49d9-bc3f-4874adb47b8d",
          "name": "get-account-bandwidth",
          "request": {
            "url": "http://api.steemjs.com/get_account_bandwidth?account=%7B%7D&bandwidthType=%7B%7D",
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
            "description": "get_account_bandwidth"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd3e9730-4cf0-483f-a46c-b0f5db2bda6d"
            }
          ]
        },
        {
          "id": "0f92a99b-9a5e-4906-9408-98df4ea80d64",
          "name": "get-savings-withdraw-from",
          "request": {
            "url": "http://api.steemjs.com/get_savings_withdraw_from?account=%7B%7D",
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
            "description": "get_savings_withdraw_from"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f866ac6-163a-49bf-b077-d06286c06c8c"
            }
          ]
        },
        {
          "id": "05724ee7-1fb6-4e3c-9d95-0984aec72411",
          "name": "get-savings-withdraw-to",
          "request": {
            "url": "http://api.steemjs.com/get_savings_withdraw_to?account=%7B%7D",
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
            "description": "get_savings_withdraw_to"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ed6e23d-c0dc-401b-8d15-6b8014d1a442"
            }
          ]
        }
      ]
    },
    {
      "name": "Number",
      "item": [
        {
          "id": "364ec632-c003-4f70-b2fd-b5d26f30f31c",
          "name": "get-number-of-accounts-from-steem",
          "request": {
            "url": "http://api.steemjs.com/get_account_count",
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
            "description": "Get Number of Accounts from Steem"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87ff75c4-d925-4dde-97ec-da9bc0fd6222"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "0390316f-2869-464d-b140-fbb4bcf524cf",
          "name": "lookup-witness-accounts-regex-search",
          "request": {
            "url": "http://api.steemjs.com/lookup_witness_accounts?limit=%7B%7D&lowerBoundName=%7B%7D",
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
            "description": "lookup_witness_accounts regex search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c332af3b-257e-434d-a03e-43f7f88c9f07"
            }
          ]
        },
        {
          "id": "0c9cc845-8313-4b74-a888-51cffb9258a3",
          "name": "lookup-account-names-example-of-accountnames-goodkarma-fabien",
          "request": {
            "url": "http://api.steemjs.com/lookup_account_names?accountNames=%7B%7D",
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
            "description": "lookup_account_names example of accountNames [\"good-karma\", \"fabien\"]"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "852d3971-29d1-4e62-bce5-2249bbbf10f4"
            }
          ]
        },
        {
          "id": "d16db916-8bf6-47f6-b94d-422d7a7d76ea",
          "name": "lookup-accounts-regex-search",
          "request": {
            "url": "http://api.steemjs.com/lookup_accounts?limit=%7B%7D&lowerBoundName=%7B%7D",
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
            "description": "lookup_accounts regex search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0132e5b2-12d3-45e5-92ad-aba95ac60264"
            }
          ]
        }
      ]
    },
    {
      "name": "Witness",
      "item": [
        {
          "id": "48b899c6-17cd-4ab0-bf97-814117f4b4d3",
          "name": "witness-update",
          "request": {
            "url": "http://api.steemjs.com/witness_update?block_signing_key=%7B%7D&fee=%7B%7D&owner=%7B%7D&props=%7B%7D&url=%7B%7D",
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
            "description": "witness_update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40b9d291-4224-4a04-9b58-e6d7d2a54a61"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "f54c9702-83df-4584-8802-6aa06cc844fd",
          "name": "account-history",
          "request": {
            "url": "http://api.steemjs.com/get_account_history?account=%7B%7D&from=%7B%7D&limit=%7B%7D",
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
            "description": "Account history"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2447f353-1e08-4d78-8b92-0f484df1c281"
            }
          ]
        },
        {
          "id": "20e09960-8e79-49b1-8a0c-8feade06e6f2",
          "name": "get-accounts-from-steem",
          "request": {
            "url": "http://api.steemjs.com/get_accounts?names=%5B%7B%7D%5D",
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
            "description": "Get Accounts from Steem"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bce5d7e0-4828-4e31-9a7d-77daa3d8991b"
            }
          ]
        }
      ]
    }
  ]
}