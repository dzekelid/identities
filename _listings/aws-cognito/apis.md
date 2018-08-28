---
name: AWS Cognito
x-slug: aws-cognito
description: Amazon Cognito lets you easily add user sign-up and sign-in to your mobile
  and web apps. With Amazon Cognito, you also have the options to authenticate users
  through social identity providers such as Facebook, Twitter, or Amazon, with SAML
  identity solutions, or by using your own identity system. In addition, Amazon Cognito
  enables you to save data locally on users devices, allowing your applications to
  work even when the devices are offline. You can then synchronize data across users
  devices so that their app experience remains consistent regardless of the device
  they use. With Amazon Cognito, you can focus on creating great app experiences instead
  of worrying about building, securing, and scaling a solution to handle user management,
  authentication, and sync across devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Identities
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Cognito Merged API - Delete Identities
  x-api-slug: actiondeleteidentities-get
  description: Deletes identities from an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentities-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity
  x-api-slug: actiondescribeidentity-get
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Credentials For Identity
  x-api-slug: actiongetcredentialsforidentity-get
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Id
  x-api-slug: actiongetid-get
  description: Generates (or retrieves) a Cognito ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetid-get-openapi.md
- name: AWS Cognito Merged API - List Identities
  x-api-slug: actionlistidentities-get
  description: Lists the identities in a pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentities-get-openapi.md
- name: AWS Cognito Merged API - Unlink Identity
  x-api-slug: actionunlinkidentity-get
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito Merged API - Merge Developer Identities
  x-api-slug: actionmergedeveloperidentities-get
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito Merged API - Bulk Publish
  x-api-slug: actionbulkpublish-get
  description: Initiates a bulk publish of all existing datasets for an Identity Pool
    to the configured stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-openapi.md
- name: AWS Cognito Merged API - Bulk Publish
  x-api-slug: actionbulkpublish-get
  description: Initiates a bulk publish of all existing datasets for an Identity Pool
    to the configured stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-openapi.md
- name: AWS Cognito Merged API - Bulk Publish
  x-api-slug: actionbulkpublish-get
  description: Initiates a bulk publish of all existing datasets for an Identity Pool
    to the configured stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionbulkpublish-get-openapi.md
- name: AWS Cognito Merged API - Create Identity Pool
  x-api-slug: actioncreateidentitypool-get
  description: Creates a new identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Create Identity Pool
  x-api-slug: actioncreateidentitypool-get
  description: Creates a new identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Create Identity Pool
  x-api-slug: actioncreateidentitypool-get
  description: Creates a new identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actioncreateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Delete Identity Pool
  x-api-slug: actiondeleteidentitypool-get
  description: Deletes a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Delete Identity Pool
  x-api-slug: actiondeleteidentitypool-get
  description: Deletes a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Delete Identity Pool
  x-api-slug: actiondeleteidentitypool-get
  description: Deletes a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondeleteidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity
  x-api-slug: actiondescribeidentity-get
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity
  x-api-slug: actiondescribeidentity-get
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity
  x-api-slug: actiondescribeidentity-get
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool
  x-api-slug: actiondescribeidentitypool-get
  description: |-
    Gets details about a particular identity pool, including the pool name, ID
             description, creation date, and current number of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool
  x-api-slug: actiondescribeidentitypool-get
  description: |-
    Gets details about a particular identity pool, including the pool name, ID
             description, creation date, and current number of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool
  x-api-slug: actiondescribeidentitypool-get
  description: |-
    Gets details about a particular identity pool, including the pool name, ID
             description, creation date, and current number of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool Usage
  x-api-slug: actiondescribeidentitypoolusage-get
  description: Gets usage details (for example, data storage) about a particular identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool Usage
  x-api-slug: actiondescribeidentitypoolusage-get
  description: Gets usage details (for example, data storage) about a particular identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Pool Usage
  x-api-slug: actiondescribeidentitypoolusage-get
  description: Gets usage details (for example, data storage) about a particular identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Usage
  x-api-slug: actiondescribeidentityusage-get
  description: Gets usage information for an identity, including number of datasets
    and data usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Usage
  x-api-slug: actiondescribeidentityusage-get
  description: Gets usage information for an identity, including number of datasets
    and data usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-openapi.md
- name: AWS Cognito Merged API - Describe Identity Usage
  x-api-slug: actiondescribeidentityusage-get
  description: Gets usage information for an identity, including number of datasets
    and data usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiondescribeidentityusage-get-openapi.md
- name: AWS Cognito Merged API - Get Credentials For Identity
  x-api-slug: actiongetcredentialsforidentity-get
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Credentials For Identity
  x-api-slug: actiongetcredentialsforidentity-get
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Credentials For Identity
  x-api-slug: actiongetcredentialsforidentity-get
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Configuration
  x-api-slug: actiongetidentitypoolconfiguration-get
  description: Gets the configuration settings of an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Configuration
  x-api-slug: actiongetidentitypoolconfiguration-get
  description: Gets the configuration settings of an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Configuration
  x-api-slug: actiongetidentitypoolconfiguration-get
  description: Gets the configuration settings of an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Roles
  x-api-slug: actiongetidentitypoolroles-get
  description: Gets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Roles
  x-api-slug: actiongetidentitypoolroles-get
  description: Gets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Get Identity Pool Roles
  x-api-slug: actiongetidentitypoolroles-get
  description: Gets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Get Open Id Token For Developer Identity
  x-api-slug: actiongetopenidtokenfordeveloperidentity-get
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Open Id Token For Developer Identity
  x-api-slug: actiongetopenidtokenfordeveloperidentity-get
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Get Open Id Token For Developer Identity
  x-api-slug: actiongetopenidtokenfordeveloperidentity-get
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pools
  x-api-slug: actionlistidentitypools-get
  description: Lists all of the Cognito identity pools registered for your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pools
  x-api-slug: actionlistidentitypools-get
  description: Lists all of the Cognito identity pools registered for your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pools
  x-api-slug: actionlistidentitypools-get
  description: Lists all of the Cognito identity pools registered for your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypools-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pool Usage
  x-api-slug: actionlistidentitypoolusage-get
  description: Gets a list of identity pools registered with Cognito.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pool Usage
  x-api-slug: actionlistidentitypoolusage-get
  description: Gets a list of identity pools registered with Cognito.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - List Identity Pool Usage
  x-api-slug: actionlistidentitypoolusage-get
  description: Gets a list of identity pools registered with Cognito.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlistidentitypoolusage-get-openapi.md
- name: AWS Cognito Merged API - Lookup Developer Identity
  x-api-slug: actionlookupdeveloperidentity-get
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Lookup Developer Identity
  x-api-slug: actionlookupdeveloperidentity-get
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Lookup Developer Identity
  x-api-slug: actionlookupdeveloperidentity-get
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Merge Developer Identities
  x-api-slug: actionmergedeveloperidentities-get
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito Merged API - Merge Developer Identities
  x-api-slug: actionmergedeveloperidentities-get
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito Merged API - Merge Developer Identities
  x-api-slug: actionmergedeveloperidentities-get
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Configuration
  x-api-slug: actionsetidentitypoolconfiguration-get
  description: Sets the necessary configuration for push sync.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Configuration
  x-api-slug: actionsetidentitypoolconfiguration-get
  description: Sets the necessary configuration for push sync.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Configuration
  x-api-slug: actionsetidentitypoolconfiguration-get
  description: Sets the necessary configuration for push sync.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Roles
  x-api-slug: actionsetidentitypoolroles-get
  description: Sets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Roles
  x-api-slug: actionsetidentitypoolroles-get
  description: Sets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Set Identity Pool Roles
  x-api-slug: actionsetidentitypoolroles-get
  description: Sets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionsetidentitypoolroles-get-openapi.md
- name: AWS Cognito Merged API - Unlink Developer Identity
  x-api-slug: actionunlinkdeveloperidentity-get
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Developer Identity
  x-api-slug: actionunlinkdeveloperidentity-get
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Developer Identity
  x-api-slug: actionunlinkdeveloperidentity-get
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Identity
  x-api-slug: actionunlinkidentity-get
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Identity
  x-api-slug: actionunlinkidentity-get
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Identity
  x-api-slug: actionunlinkidentity-get
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito Merged API - Update Identity Pool
  x-api-slug: actionupdateidentitypool-get
  description: Updates a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Update Identity Pool
  x-api-slug: actionupdateidentitypool-get
  description: Updates a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Update Identity Pool
  x-api-slug: actionupdateidentitypool-get
  description: Updates a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionupdateidentitypool-get-openapi.md
- name: AWS Cognito Merged API - Lookup Developer Identity
  x-api-slug: actionlookupdeveloperidentity-get
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Unlink Developer Identity
  x-api-slug: actionunlinkdeveloperidentity-get
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito Merged API - Lookup Developer Identity
  x-api-slug: actionlookupdeveloperidentity-get
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Amazon Web Services, Authentication, Social, Facebook, Twitter, Stack Network,
    API Service Provider, API Service Provider, API Provider, Identities, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.codedeploy.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.cognito.stack.network
- type: x-blog
  url: https://aws.amazon.com/cognito/dev-resources/#blogposts
- type: x-documentation
  url: http://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitosync/latest/APIReference/Welcome.html
- type: x-faq
  url: http://aws.amazon.com/cognito/faqs
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=173
- type: x-pricing
  url: http://aws.amazon.com/cognito/pricing
- type: x-sdk
  url: https://aws.amazon.com/cognito/dev-resources/#documentation
- type: x-slides
  url: https://aws.amazon.com/cognito/dev-resources/#slides
- type: x-videos
  url: https://aws.amazon.com/cognito/dev-resources/#videos
- type: x-website
  url: https://aws.amazon.com/cognito/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---