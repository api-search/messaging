---
name: Mailchimp
description: >-
  Mailchimp’s developer tools provide everything you need to integrate your data
  with intelligent marketing tools and event-driven transactional email.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/mailchimp.yml
created: 2023/11/23
modified: 2023/11/23
specificationVersion: '0.16'
tags: []
apis:
  - name: 'Mailchimp Marketing API '
    description: >-
      The Mailchimp Marketing API provides programmatic access to Mailchimp data
      and functionality, allowing developers to build custom features to do
      things like sync email activity and campaign analytics with their
      database, manage audiences and campaigns, and more.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://mailchimp.com/developer/marketing/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://mailchimp.com/developer/marketing/docs/fundamentals/
      - type: OpenAPI
        url: properties/mailchimp-openapi-original.yml
      - type: Integrations
        url: https://mailchimp.com/developer/marketing/docs/integrations/
      - type: Errors
        url: https://mailchimp.com/developer/marketing/docs/errors/
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.mailchimp.com/schema/3.0/Swagger.json?expand-openapi-search.yml
    aid: mailchimp:mailchimp-marketing-api
  - name: Mailchimp Transactional API
    description: >-
      Mailchimp Transactional is a powerful email delivery service that lets you
      send personalized, one-to-one emails like password resets, order
      confirmations, and welcome messages. 
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://mailchimp.com/developer/transactional/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://mailchimp.com/developer/transactional/docs/fundamentals/
      - type: Guide
        url: https://mailchimp.com/developer/transactional/guides/quick-start/
      - type: Authentication
        url: >-
          https://mailchimp.com/developer/transactional/docs/authentication-delivery/
      - type: Webhooks
        url: https://mailchimp.com/developer/transactional/docs/webhooks/
    overlays: []
    aid: mailchimp:mailchimp-transactional-api
  - name: MailChimp Open Commerce
    description: >-
      An open source, API-first, modular commerce stack made for technical,
      growth-minded retailers. Use our open source platform to build the
      e-commerce solution that fits your business, on your own servers or in the
      cloud.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://mailchimp.com/developer/open-commerce/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://mailchimp.com/developer/open-commerce/docs/fundamentals/
      - type: Guides
        url: https://mailchimp.com/developer/open-commerce/guides/quick-start/
      - type: GraphQL Playground
        url: https://mailchimp.com/developer/open-commerce/playground/
    overlays: []
    aid: mailchimp:mailchimp-open-commerce
common:
  - type: Tools
    url: https://mailchimp.com/developer/tools/
  - type: Portal
    url: https://mailchimp.com/developer/
  - type: Change Log
    url: https://mailchimp.com/developer/release-notes/
  - type: Blog
    url: https://mailchimp.com/developer/blog/
  - type: Plans
    url: https://mailchimp.com/pricing/marketing/
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: mailchimp
---