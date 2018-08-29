swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 1
info:
  title: Capital One DevExchange
  description: nessie-is-capital-ones-hackathon-api-that-gives-you-access-to-a-multitude-of-real-publicfacing-data--such-as-atm-and-bank-branch-locations--along-with-mock-customer-account-data--use-http-requests-to-set-up-peertopeer-transactions-simulate-a-weekly-paycheck-or-even-schedule-bills-for-customers-this-is-all-structured-in-a-way-that-resembles-how-we-actually-run-things-here-at-capital-one-
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/withdrawals:
    get:
      summary: Get all withdrawals
      description: Returns the withdrawals that you are involved in.
      operationId: returns-the-withdrawals-that-you-are-involved-in
      x-api-path-slug: accountsidwithdrawals-get
      parameters:
      - in: path
        name: id
        description: ID of account associated with the withdrawal
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Accounts
      - ""
      - Withdrawals
    post:
      summary: Create a withdrawal
      description: Creates a withdrawal where the account with the ID specified is
        debitted.
      operationId: creates-a-withdrawal-where-the-account-with-the-id-specified-is-debitted
      x-api-path-slug: accountsidwithdrawals-post
      parameters:
      - in: body
        name: body
        description: Withdrawal to be created
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of account receiver of withdrawal
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Accounts
      - ""
      - Withdrawals
  /withdrawals/{id}:
    get:
      summary: Get withdrawal by id
      description: Returns the withdrawal with the specific id
      operationId: returns-the-withdrawal-with-the-specific-id
      x-api-path-slug: withdrawalsid-get
      parameters:
      - in: path
        name: id
        description: ID of the withdrawal that is being fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Withdrawals
    put:
      summary: Update a specific existing withdrawal
      description: Updates the specific withdrawal
      operationId: updates-the-specific-withdrawal
      x-api-path-slug: withdrawalsid-put
      parameters:
      - in: body
        name: body
        description: withdrawal to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of the withdrawal that is being updated
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Withdrawals
    delete:
      summary: Delete a specific existing withdrawal
      description: Deletes the specific withdrawal
      operationId: deletes-the-specific-withdrawal
      x-api-path-slug: withdrawalsid-delete
      parameters:
      - in: path
        name: id
        description: ID of the withdrawal that is being deleted
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Withdrawals