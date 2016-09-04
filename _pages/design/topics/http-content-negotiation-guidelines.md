---
layout: topic
title: Content negociation and media types
permalink: /design/topics/http-content-negotiation
sort: HTTP Protocol_Content negociation and media types
topic_id: http-content-negotiation
topic_category: HTTP Protocol
topic_name: Content negociation and media types
topic_description: 'How to describe your API data format and/or propose different formats (like json, yaml, xml atom, ...)'
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
      - name: Formats
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#formats'
      - name: API Payload format encoding
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#api-payload-format-encoding'
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
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
      - name: 3.5.1 Standard Headers
        quote: 'Accept header, Content-Type header'
        url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
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
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
        quote: Accept Content Type
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
        quote: Content Type
      - name: Clients-specified response format
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#7101-clients-specified-response-format'
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
      - name: Representations
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#representations'
      - name: Content-Types
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#content-types'
  - guideline_id: white-house-web-api-standards
    guideline_title: White House Web API Standards
    guideline_type: github
    guideline_url: 'https://github.com/WhiteHouse/api-standards'
    guideline_company: White House
    guideline_companyLogoUrl: /media/logos/whitehouse.png
    guideline_companyUrl: 'https://www.whitehouse.gov/developers'
    guideline_screenshotUrl: /media/screenshots/white-house-web-api-standards.png
    guideline_date: 2015-02-24T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/white-house-web-api-standards
      guidelineTopics:
        href: /design/guidelines/white-house-web-api-standards/topics
    references:
      - name: General guidelines for RESTful URLs
        quote: 'Formats should be in the form of api/v2/resource/{id}.json'
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
      - name: Use Media Type Versioning
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-use-media-type-versioning'
      - name: Modify the Content-Type for Embedded Resources
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
      - name: Use Application-Specific Content Types
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-applicationspecific-content-types'
---