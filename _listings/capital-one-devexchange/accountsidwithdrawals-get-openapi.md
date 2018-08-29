---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Get all withdrawals
  description: Returns the withdrawals that you are involved in.
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