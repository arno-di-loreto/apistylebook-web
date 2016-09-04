---
layout: topic
title: HEAD
permalink: /design/topics/http-methods-head
sort: HTTP Methods_HEAD
topic_id: http-methods-head
topic_category: HTTP Methods
topic_name: HEAD
topic_description: When to use HTTP method HEAD
guidelines:
  - guideline_id: ausdto-api-design-guide
    guideline_title: API Design Guide
    guideline_type: website
    guideline_url: 'https://apiguide.readthedocs.io/en/latest/index.html'
    guideline_company: Australian Digital Transformation Office
    guideline_companyLogoUrl: /media/logos/ausdto.png
    guideline_companyUrl: 'https://www.dto.gov.au/'
    guideline_screenshotUrl: /media/screenshots/ausdto-api-design-guide.png
    guideline_date: 2015-10-20T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/ausdto-api-design-guide
      guidelineTopics:
        href: /design/guidelines/ausdto-api-design-guide/topics
    references:
      - name: HEAD /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines'
      - name: HEAD /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines-1234'
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
      - name: 3.6.6 HEAD
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: HEAD
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#head'
---