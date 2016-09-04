---
layout: topic
title: Data format
permalink: /design/topics/data-format
sort: Data_Data format
topic_id: data-format
topic_category: Data
topic_name: Data format
topic_description: which data format use
guidelines:
  - guideline_id: atlassian-rest-api-design-guidelines-version-1
    guideline_title: Atlassian REST API Design Guidelines version 1
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-design-guidelines-version-1.png
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1/topics
    references:
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Representations (Content Types) of Entities
      - name: 'Appendix B: Basic Data Types'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixB:BasicDataTypes'
  - guideline_id: atlassian-rest-api-policy
    guideline_title: Atlassian REST API Policy
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-policy.png
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-policy
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-policy/topics
    references:
      - name: Compatibility policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
      - name: Structured representations (application/json)
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Structuredrepresentations(application/json)'
      - name: Forward compatibility
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Forwardcompatibility'
  - guideline_id: cisco-api-design-guide
    guideline_title: API Design Guide
    guideline_type: github
    guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
    guideline_company: Cisco
    guideline_companyLogoUrl: /media/logos/cisco.png
    guideline_companyUrl: 'http://developer.cisco.com/'
    guideline_screenshotUrl: /media/screenshots/cisco-api-design-guide.png
    guideline_date: 2015-08-21T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline_attachedDocuments:
      - name: REST API Design Principles
        description: A summary of common REST API design constraints and conventions
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md'
        type: github
        referenced:
          - name: Preface
            url: 'https://github.com/CiscoDevNet/api-design-guide#1-preface'
      - name: Tracking ID flow
        description: A sequence diagram explaning
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/trackingid-flow.png'
        type: github
        referenced:
          - name: TrackingID Header
            description: A sequence diagram explaning the use of the tracking ID
            url: 'https://github.com/CiscoDevNet/api-design-guide#352-trackingid-header'
    guideline_remarks:
      - 'broken links due to typo error in https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
    guideline__links:
      self:
        href: /design/guidelines/cisco-api-design-guide
      guidelineTopics:
        href: /design/guidelines/cisco-api-design-guide/topics
    references:
      - name: 3.3 Representations
        quote: ... prefer the native JSON boolean type ...
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
  - guideline_id: haufe-api-styleguide
    guideline_title: Haufe API style guide
    guideline_type: github
    guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
    guideline_company: Haufe
    guideline_companyLogoUrl: /media/logos/haufe.png
    guideline_companyUrl: 'http://dev.haufe.com/'
    guideline_screenshotUrl: /media/screenshots/haufe-api-styleguide.png
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/haufe-api-styleguide
      guidelineTopics:
        href: /design/guidelines/haufe-api-styleguide/topics
    references:
      - name: Hypermedia Response Format
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/response-format/response-format.md'
      - name: Type Formatting
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md'
      - name: Message Schema and Postel's Law
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
  - guideline_id: heroku-http-api-design-guide
    guideline_title: HTTP API Design Guide
    guideline_type: gitbook
    guideline_url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
    guideline_company: Heroku
    guideline_companyLogoUrl: /media/logos/heroku.png
    guideline_companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
    guideline_screenshotUrl: /media/screenshots/heroku-http-api-design-guide.png
    guideline_date: 2016-07-05T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/heroku-http-api-design-guide
      guidelineTopics:
        href: /design/guidelines/heroku-http-api-design-guide/topics
    references:
      - name: Accept serialized JSON in request bodies
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/accept-serialized-json-in-request-bodies.html'
      - name: Provide standard timestamps
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
      - name: Nest foreign key relations
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/nest-foreign-key-relations.html'
      - name: Keep JSON minified in all responses
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/keep-json-minified-in-all-responses.html'
  - guideline_id: microsoft-rest-api-guidelines
    guideline_title: Microsoft REST API Guidelines
    guideline_type: github
    guideline_url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md'
    guideline_company: Microsoft
    guideline_companyLogoUrl: /media/logos/microsoft.png
    guideline_companyUrl: 'https://opensource.microsoft.com/'
    guideline_screenshotUrl: /media/screenshots/microsoft-rest-api-guidelines.png
    guideline_date: 2016-07-19T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/microsoft-rest-api-guidelines
      guidelineTopics:
        href: /design/guidelines/microsoft-rest-api-guidelines/topics
    references:
      - name: Response Formats
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#710-response-formats'
      - name: JSON standardizations
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#11-json-standardizations'
  - guideline_id: redhat-thoughts-on-restful-api-design
    guideline_title: Thoughts on RESTful API Design
    guideline_type: website
    guideline_url: 'http://restful-api-design.readthedocs.io/en/latest/'
    guideline_company: Red Hat
    guideline_companyLogoUrl: /media/logos/redhat.png
    guideline_companyUrl: 'https://www.redhat.com/'
    guideline_screenshotUrl: /media/screenshots/redhat-thoughts-on-restful-api-design.png
    guideline_authors:
      - name: Geert Jansen
        twitter: 1geertj
    guideline_date: 2012-11-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design
      guidelineTopics:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design/topics
    references:
      - name: Resource Data
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#resource-data'
  - guideline_id: zalando-restful-api-guidelines
    guideline_title: RESTFul API Guidelines
    guideline_type: website
    guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
    guideline_company: Zalando
    guideline_companyLogoUrl: /media/logos/zalando.png
    guideline_companyUrl: 'https://tech.zalando.de/'
    guideline_screenshotUrl: /media/screenshots/zalando-restful-api-guidelines.png
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-08-28T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/zalando-restful-api-guidelines
      guidelineTopics:
        href: /design/guidelines/zalando-restful-api-guidelines/topics
    references:
      - name: Property Values
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
      - name: Date property values should conform to RFC 3399
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
      - name: Time durations and intervals could conform to ISO 8601
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
      - name: Data Formats
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html'
      - name: Common Data Objects
        url: 'http://zalando.github.io/restful-api-guidelines/common-data-objects/CommonDataObjects.html'
---