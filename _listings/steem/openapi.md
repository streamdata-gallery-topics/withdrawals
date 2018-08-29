swagger: "2.0"
x-collection-name: Steem
x-complete: 1
info:
  title: Interactive Steem API
  description: interactive-steem-api-lets-you-interact-with-steem-blockchain-and-make-a-request-get-output-and-start-implementing-new-apps-apis-have-default-parameters-set-to-get-you-started-and-see-how-request-works--api-list-is-compiled-from-steem-githubhttpsgithub-comsteemitsteem-1httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappapi-hpp-and-2httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappdatabase-api-hpp--if-you-want-to-contribute-documenting-detail-of-properties-and-output-contact-goodkarmahttpssteemit-chatdirectgoodkarma--you-can-also-check-full-list-here-steem-jshttpssteemjs-com
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_withdraw_routes:
    get:
      summary: get_withdraw_routes
      description: get_withdraw_routes
      operationId: get-withdraw-routes
      x-api-path-slug: get-withdraw-routes-get
      parameters:
      - in: query
        name: account
        description: account name
      - in: query
        name: withdrawRouteType
        description: withdrawRouteType
      responses:
        200:
          description: OK
      tags:
      - Get
      - Withdraw
      - Routes
  /get_savings_withdraw_from:
    get:
      summary: get_savings_withdraw_from
      description: get_savings_withdraw_from
      operationId: get-savings-withdraw-from
      x-api-path-slug: get-savings-withdraw-from-get
      parameters:
      - in: query
        name: account
        description: account name
      responses:
        200:
          description: OK
      tags:
      - Get
      - Savings
      - Withdraw
      - From
  /get_savings_withdraw_to:
    get:
      summary: get_savings_withdraw_to
      description: get_savings_withdraw_to
      operationId: get-savings-withdraw-to
      x-api-path-slug: get-savings-withdraw-to-get
      parameters:
      - in: query
        name: account
        description: account name
      responses:
        200:
          description: OK
      tags:
      - Get
      - Savings
      - Withdraw
      - To