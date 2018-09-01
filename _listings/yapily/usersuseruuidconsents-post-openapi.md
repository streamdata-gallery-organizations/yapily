---
swagger: "2.0"
x-collection-name: Yapily
x-complete: 0
info:
  title: Yapily Post consent
  description: Post consent.
  version: 1.0.0
host: api.yapily.com:443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts:
    get:
      summary: Get accounts
      description: Get accounts.
      operationId: getAccountsUsingGET
      x-api-path-slug: accounts-get
      parameters:
      - in: header
        name: consent
        description: Consent Token
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /accounts/{accountId}:
    get:
      summary: Get account
      description: Get account.
      operationId: getAccountUsingGET
      x-api-path-slug: accountsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: accountId
      - in: header
        name: consent
        description: Consent Token
      responses:
        200:
          description: OK
      tags:
      - Account
  /accounts/{accountId}/transactions:
    get:
      summary: Get account transactions
      description: Get account transactions.
      operationId: getTransactionsUsingGET
      x-api-path-slug: accountsaccountidtransactions-get
      parameters:
      - in: path
        name: accountId
        description: accountId
      - in: header
        name: consent
        description: Consent Token
      responses:
        200:
          description: OK
      tags:
      - Account
      - Transactions
  /identity:
    get:
      summary: Get identity
      description: Get identity.
      operationId: identityUsingGET
      x-api-path-slug: identity-get
      parameters:
      - in: header
        name: consent
        description: Consent Token
      responses:
        200:
          description: OK
      tags:
      - Identity
  /institutions:
    get:
      summary: Retrieves the list of institutions available in Yapily
      description: Retrieves the list of institutions available in yapily.
      operationId: getInstitutionsUsingGET
      x-api-path-slug: institutions-get
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - List
      - Institutions
      - Available
      - In
      - Yapily
  /institutions/{institutionId}:
    get:
      summary: Retrieves details of a specific institution available in Yapily
      description: Retrieves details of a specific institution available in yapily.
      operationId: getInstitutionUsingGET
      x-api-path-slug: institutionsinstitutionid-get
      parameters:
      - in: path
        name: institutionId
        description: institutionId
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - Details
      - Specific
      - Institution
      - Available
      - In
      - Yapily
  /institutions/{institutionId}/personal-current-accounts:
    get:
      summary: Retrieves details of personal current accounts for an institution
      description: Retrieves details of personal current accounts for an institution.
      operationId: getPersonalCurrentAccountsUsingGET
      x-api-path-slug: institutionsinstitutionidpersonalcurrentaccounts-get
      parameters:
      - in: path
        name: institutionId
        description: institutionId
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - Details
      - Personal
      - Current
      - Accountsan
      - Institution
  /me:
    get:
      summary: Returns the details of the application which owns the request credentials
      description: Returns the details of the application which owns the request credentials.
      operationId: getApplicationMeUsingGET
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Details
      - Application
      - Which
      - Owns
      - Request
      - Credentials
  /users:
    get:
      summary: Get application users
      description: Get application users.
      operationId: getUsersUsingGET
      x-api-path-slug: users-get
      responses:
        200:
          description: OK
      tags:
      - Application
      - Users
    post:
      summary: Add an application user
      description: Add an application user.
      operationId: addUserUsingPOST
      x-api-path-slug: users-post
      parameters:
      - in: body
        name: applicationUser
        description: applicationUser
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Application
      - User
  /users/{userUuid}/consents:
    get:
      summary: Get consent
      description: Get consent.
      operationId: getUserConsentsUsingGET
      x-api-path-slug: usersuseruuidconsents-get
      parameters:
      - in: query
        name: institutionId
        description: institutionId
      - in: path
        name: userUuid
        description: userUuid
      responses:
        200:
          description: OK
      tags:
      - Consent
    post:
      summary: Post consent
      description: Post consent.
      operationId: addConsentUsingPOST
      x-api-path-slug: usersuseruuidconsents-post
      parameters:
      - in: body
        name: createConsentApiKey
        description: createConsentApiKey
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userUuid
        description: userUuid
      responses:
        200:
          description: OK
      tags:
      - Consent
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