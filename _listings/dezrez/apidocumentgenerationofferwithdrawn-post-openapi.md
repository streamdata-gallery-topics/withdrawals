---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Generates a correspondence to notify any parties of the withdrawl
    of an offer.  Uses default values where possible.
  version: 1.0.0
  description: Generates a correspondence to notify any parties of the withdrawl of
    an offer.  uses default values where possible..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/auction/{id}/withdrawlots:
    post:
      summary: To withdraw a list of properties from the auction
      description: To withdraw a list of properties from the auction.
      operationId: Auction_WithdrawLotsByidBywithdrawLotsDataContract
      x-api-path-slug: apiauctionidwithdrawlots-post
      parameters:
      - in: path
        name: id
        description: The auction ID
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: withdrawLotsDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - To
      - Withdraw
      - List
      - Of
      - Properties
      - From
      - Auction
  /api/progression/lettings/withdrawInstruction:
    post:
      summary: Withdraw a letting at the end of let
      description: Withdraw a letting at the end of let.
      operationId: LettingsProgression_WithdrawInstructionBylettingInstructionCommandData
      x-api-path-slug: apiprogressionlettingswithdrawinstruction-post
      parameters:
      - in: body
        name: lettingInstructionCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Withdraw
      - Letting
      - At
      - End
      - Of
      - Let
  /api/progression/lettings/completeletting:
    post:
      summary: Withdraw a letting at the end of let
      description: Withdraw a letting at the end of let.
      operationId: LettingsProgression_CompleteLettingBycompleteCommandData
      x-api-path-slug: apiprogressionlettingscompleteletting-post
      parameters:
      - in: body
        name: completeCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Withdraw
      - Letting
      - At
      - End
      - Of
      - Let
  /api/receipt/withdrawfunds:
    post:
      summary: Withdraw funds for the agent
      description: Withdraw funds for the agent.
      operationId: Receipt_WithdrawFundsBywithdrawFundsDataContract
      x-api-path-slug: apireceiptwithdrawfunds-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: withdrawFundsDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Withdraw
      - Fundsthe
      - Agent
  /api/documentgeneration/offerwithdrawn:
    post:
      summary: Generates a correspondence to notify any parties of the withdrawl of
        an offer.  Uses default values where possible.
      description: Generates a correspondence to notify any parties of the withdrawl
        of an offer.  uses default values where possible..
      operationId: DocumentGeneration_OfferwithdrawnLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationofferwithdrawn-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - To
      - Notify
      - Any
      - Parties
      - Of
      - Withdrawl
      - Of
      - Offer
      - ""
      - ""
      - Uses
      - Default
      - Values
      - Where
      - Possible
  /api/documentgeneration/withdrawninstruction:
    post:
      summary: Generates a Withdrawn Instruction letter correspondence to the vendor
        of a particular marketing role
      description: Generates a withdrawn instruction letter correspondence to the
        vendor of a particular marketing role.
      operationId: DocumentGeneration_GenerateWithdrawnInstructionLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationwithdrawninstruction-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Withdrawn
      - Instruction
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/progression/withdrawvaluation:
    put:
      summary: Add WithdrawVal to a property sales role
      description: Add withdrawval to a property sales role.
      operationId: Progression_WithdrawValuationBywithdrawValuationDataContract
      x-api-path-slug: apiprogressionwithdrawvaluation-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: withdrawValuationDataContract
        description: Details of the progression withdrawal
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - WithdrawVal
      - To
      - Property
      - Sales
      - Role
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