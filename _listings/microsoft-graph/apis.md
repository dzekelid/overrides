---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Overrides
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Overrides
  x-api-slug: meinferenceclassificationoverrides-get
  description: List overrides Get the overrides that a user has set up to always classify
    messages from certain senders in specific ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-get-openapi.md
- name: Microsoft Graph API - List Overrides
  x-api-slug: usersidinferenceclassificationoverrides-get
  description: List overrides Get the overrides that a user has set up to always classify
    messages from certain senders in specific ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-get-openapi.md
- name: Microsoft Graph API - Create Inference Classification Override
  x-api-slug: meinferenceclassificationoverrides-post
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API - Create Inference Classification Override
  x-api-slug: usersidinferenceclassificationoverrides-post
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API - Delete Inference Classification Override
  x-api-slug: meinferenceclassificationoverridesid-delete
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-openapi.md
- name: Microsoft Graph API - Delete Inference Classification Override
  x-api-slug: usersidinferenceclassificationoverridesid-delete
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-openapi.md
- name: Microsoft Graph API - Create Inference Classification Override
  x-api-slug: meinferenceclassificationoverrides-post
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API - Create Inference Classification Override
  x-api-slug: usersidinferenceclassificationoverrides-post
  description: Create inferenceClassificationOverride Create an override for a sender
    identified by an SMTP address. Future messages from that SMTP address will be
    consistently classified as specified in the override.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverrides-post-openapi.md
- name: Microsoft Graph API - Delete Inference Classification Override
  x-api-slug: meinferenceclassificationoverridesid-delete
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/meinferenceclassificationoverridesid-delete-openapi.md
- name: Microsoft Graph API - Delete Inference Classification Override
  x-api-slug: usersidinferenceclassificationoverridesid-delete
  description: Delete inferenceClassificationOverride Delete an override specified
    by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/overrides/master/_listings/microsoft-graph/usersidinferenceclassificationoverridesid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---