---
name: Yapily
x-slug: yapily
description: Yapily is how people connect to banks, easily! We are an API Only technology
  provider whose mission is to enable innovative products to connect to banks, empowering
  a new generation of financial services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
x-kinRank: "0"
x-alexaRank: "7167103"
tags: Yapily
created: "2018-06-27"
modified: "2018-06-27"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/apis.md
specificationVersion: "0.14"
apis:
- name: Yapily Get accounts
  x-api-slug: yapily
  description: Get accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////accounts
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accounts-get-openapi.md
- name: Yapily Get account
  x-api-slug: yapily
  description: Get account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////accounts/{accountId}
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accountsaccountid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accountsaccountid-get-openapi.md
- name: Yapily Get account transactions
  x-api-slug: yapily
  description: Get account transactions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////accounts/{accountId}/transactions
  tags: Account,Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accountsaccountidtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/accountsaccountidtransactions-get-openapi.md
- name: Yapily Get identity
  x-api-slug: yapily
  description: Get identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////identity
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/identity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/identity-get-openapi.md
- name: Yapily Retrieves the list of institutions available in Yapily
  x-api-slug: yapily
  description: Retrieves the list of institutions available in yapily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////institutions
  tags: Retrieves,List,Institutions,Available,In,Yapily
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutions-get-openapi.md
- name: Yapily Retrieves details of a specific institution available in Yapily
  x-api-slug: yapily
  description: Retrieves details of a specific institution available in yapily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////institutions/{institutionId}
  tags: Retrieves,Details,Specific,Institution,Available,In,Yapily
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutionsinstitutionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutionsinstitutionid-get-openapi.md
- name: Yapily Retrieves details of personal current accounts for an institution
  x-api-slug: yapily
  description: Retrieves details of personal current accounts for an institution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////institutions/{institutionId}/personal-current-accounts
  tags: Retrieves,Details,Personal,Current,Accountsan,Institution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutionsinstitutionidpersonalcurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/institutionsinstitutionidpersonalcurrentaccounts-get-openapi.md
- name: Yapily Returns the details of the application which owns the request credentials
  x-api-slug: yapily
  description: Returns the details of the application which owns the request credentials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////me
  tags: Returns,Details,Application,Which,Owns,Request,Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/me-get-openapi.md
- name: Yapily Get application users
  x-api-slug: yapily
  description: Get application users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users
  tags: Application,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/users-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/users-get-openapi.md
- name: Yapily Add an application user
  x-api-slug: yapily
  description: Add an application user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users
  tags: Application,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/users-post-openapi.md
- name: Yapily Get consent
  x-api-slug: yapily
  description: Get consent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users/{userUuid}/consents
  tags: Consent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/usersuseruuidconsents-get-openapi.md
- name: Yapily Post consent
  x-api-slug: yapily
  description: Post consent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users/{userUuid}/consents
  tags: Consent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/usersuseruuidconsents-post-openapi.md
- name: Yapily Delete consent
  x-api-slug: yapily
  description: Delete consent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users/{userUuid}/consents/{consentToken}
  tags: Consent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/usersuseruuidconsentsconsenttoken-delete-openapi.md
- name: Yapily Get an application user
  x-api-slug: yapily
  description: Get an application user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users/{uuid}
  tags: Application,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/usersuuid-get-openapi.md
- name: Yapily Update an application user
  x-api-slug: yapily
  description: Update an application user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443////users/{uuid}
  tags: Application,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/usersuuid-put-openapi.md
- name: Yapily
  x-api-slug: yapily
  description: Yapily is how people connect to banks, easily! We are an API Only technology
    provider whose mission is to enable innovative products to connect to banks, empowering
    a new generation of financial services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yapily-logo.png
  humanURL: https://www.yapily.com
  baseURL: https://api.yapily.com:443//
  tags: Yapily
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yapily/master/_listings/yapily/openapi.md
x-common:
- type: x-authentication
  url: https://doc.yapily.com/#api-authentication
- type: x-documentation
  url: https://doc.yapily.com/
- type: x-email
  url: hello@yapily.com
- type: x-email
  url: developers@yapily.com
- type: x-email
  url: info@yapily.com
- type: x-getting-started
  url: https://doc.yapily.com/#get-started
- type: x-github
  url: https://github.com/yapily
- type: x-twitter
  url: https://twitter.com/YapilyLtd
- type: x-website
  url: https://www.yapily.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---