---
layout: topic
title: Date and Time
permalink: /design/topics/data-format-date-time
sort: Data_Date and Time
topic_id: data-format-date-time
topic_category: Data
topic_name: Date and Time
topic_description: How to deal with date and time data
guidelines:
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
        quote: RFC-3339
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
      - name: Dates and Times
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#dates-and-times'
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
      - name: Provide standard timestamps
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
      - name: Use UTC times formatted in ISO8601
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/use-utc-times-formatted-in-iso8601.html'
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
      - name: Guidelines for dates and times
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#112-guidelines-for-dates-and-times'
      - name: JSON serialization of dates and times
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#113-json-serialization-of-dates-and-times'
      - name: Durations
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#114-durations'
      - name: Intervals
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#115-intervals'
      - name: Repeating intervals
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#116-repeating-intervals'
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
      - name: Date property values should conform to RFC 3399
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
      - name: Time durations and intervals could conform to ISO 8601
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
      - name: Use Standard Date and Time Formats
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#must-use-standard-date-and-time-formats'
      - name: HTTP headers
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
        quote: Use the HTTP date format defined in RFC 7231
---