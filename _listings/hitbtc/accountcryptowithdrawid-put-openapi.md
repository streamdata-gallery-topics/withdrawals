---
swagger: "2.0"
x-collection-name: HitBTC
x-complete: 0
info:
  title: HitBTC Commit Withdraw Crypro
  description: Commit withdraw crypro.
  version: 1.0.0
basePath: /api/2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/crypto/withdraw:
    post:
      summary: Withdraw Crypro
      description: Withdraw crypro.
      operationId: postAccountCryptoWithdraw
      x-api-path-slug: accountcryptowithdraw-post
      parameters:
      - in: formData
        name: address
      - in: formData
        name: amount
      - in: formData
        name: autoCommit
        description: If Auto commit disabled you should commit it or rollback within
          1 hour
      - in: formData
        name: currency
      - in: formData
        name: includeFee
        description: If enabled, then fee will be subtracted from amount
      - in: formData
        name: networkFee
        description: Suggest preferred network fee
      - in: formData
        name: paymentId
      responses:
        200:
          description: OK
      tags:
      - Withdraw
      - Crypro
  /account/crypto/withdraw/{id}:
    put:
      summary: Commit Withdraw Crypro
      description: Commit withdraw crypro.
      operationId: putAccountCryptoWithdraw
      x-api-path-slug: accountcryptowithdrawid-put
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Commit
      - Withdraw
      - Crypro
    delete:
      summary: Rollback Withdraw Crypro
      description: Rollback withdraw crypro.
      operationId: deleteAccountCryptoWithdraw
      x-api-path-slug: accountcryptowithdrawid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Rollback
      - Withdraw
      - Crypro
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