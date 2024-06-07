---
name: Slack
description: >-
  Slack is a cloud-based freemium cross-platform instant messaging service
  created by Slack Technologies and currently owned by Salesforce. While
  initially developed for professional and organizational communications, it has
  also been adopted as a community platform.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/slack.yml
created: 2023/10/6
modified: 2023/10/6
specificationVersion: '0.14'
tags: []
apis:
  - name: Slack Web API
    description: >-
      The Slack Web API is an interface for querying information from and
      enacting change in a Slack workspace. Use it for individual queries, or as
      part of a more complex tapestry of platform features in a Slack app.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://api.slack.com/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://api.slack.com/docs
      - type: OpenAPI
        url: properties/slack-web-openapi-original.yml
    contact:
      - FN: Support
        url: https://api.slack.com/support
    aid: slack:slack-web-api
common:
  - type: GettingStarted
    url: https://api.slack.com/automation/quickstart
  - type: Authentication
    url: https://api.slack.com/authentication
  - type: Type
    url: https://example.com
  - type: Blog
    url: https://slack.com/blog/developers
  - type: Forum
    url: https://forums.slackcommunity.com/s/
  - type: TermsOfService
    url: https://slack.com/terms-of-service/api
  - type: Login
    url: https://slack.com/signin
  - type: SignUp
    url: https://slack.com/get-started
  - type: Tutorials
    url: https://api.slack.com/tutorials
  - type: ChangeLog
    url: https://api.slack.com/changelog
maintainers:
  - FN: API Evangelist
    url: https://apievangelisgt.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: slack
---