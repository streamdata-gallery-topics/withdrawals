---
swagger: "2.0"
x-collection-name: ChainGenie
x-complete: 0
info:
  title: ChainGenie Withdraw from bank account
  description: Withdraw crypto currency into the bank.  In sandbox mode, the account
    used is the demo account on the blockchain server. Of course, you can only withdraw
    if there is money in the account!
  version: "1.0"
host: api.chaingenie.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ethbank/withdraw:
    post:
      summary: Withdraw from bank account
      description: Withdraw crypto currency into the bank.  In sandbox mode, the account
        used is the demo account on the blockchain server. Of course, you can only
        withdraw if there is money in the account!
      operationId: EthbankWithdrawPost
      x-api-path-slug: ethbankwithdraw-post
      parameters:
      - in: header
        name: ApiKey
      - in: formData
        name: value
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Withdraw
      - From
      - Bank
      - Account
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