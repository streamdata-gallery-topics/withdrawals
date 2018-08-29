swagger: "2.0"
x-collection-name: HitBTC
x-complete: 1
info:
  title: HitBTC API
  description: create-api-keys-in-your-profile-httpshitbtc-comsettingsapikeys-and-use-public-api-key-as-username-and-secret-as-password-to-authorize-
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