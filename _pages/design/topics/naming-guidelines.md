---
layout: topic
title: Naming
permalink: /design/topics/naming
sort: Naming_Naming
topic_id: naming
topic_category: Naming
topic_name: Naming
topic_description: How to name things
guidelines:
  - guideline_id: cisco-api-design-guide
    guideline_title: API Design Guide
    guideline_type: github
    guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
    guideline_company: Cisco
    guideline_companyLogoUrl: /media/logos/cisco.png
    guideline_companyUrl: 'http://developer.cisco.com/'
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
        quote: '3.3.11 With regard to JSON representation property names, and URL query parameters, services SHOULD...'
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
  - guideline_id: cloud-foundy-cloud-controller-api-style-guide
    guideline_title: Cloud Controller API v3 Style Guide (Proposal)
    guideline_type: github
    guideline_url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
    guideline_company: Cloud Foundry
    guideline_companyLogoUrl: /media/logos/cloudfoundry.png
    guideline_companyUrl: 'https://www.cloudfoundry.org/'
    guideline_date: 2016-05-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
      guidelineTopics:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
    references:
      - name: Query Parameters
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
      - name: Field Names
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#field-names'
      - name: URL Structure
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
  - guideline_id: haufe-api-styleguide
    guideline_title: Haufe API style guide
    guideline_type: github
    guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
    guideline_company: Haufe
    guideline_companyLogoUrl: /media/logos/haufe.png
    guideline_companyUrl: 'http://dev.haufe.com/'
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/haufe-api-styleguide
      guidelineTopics:
        href: /design/guidelines/haufe-api-styleguide/topics
    references:
      - name: Building Your Resource Taxonomy
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#building-your-resource-taxonomy'
      - name: Resource naming
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#resource-naming'
  - guideline_id: heroku-http-api-design-guide
    guideline_title: HTTP API Design Guide
    guideline_type: gitbook
    guideline_url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
    guideline_company: Heroku
    guideline_companyLogoUrl: /media/logos/heroku.png
    guideline_companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
    guideline_date: 2016-07-05T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/heroku-http-api-design-guide
      guidelineTopics:
        href: /design/guidelines/heroku-http-api-design-guide/topics
    references:
      - name: Resource names
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/resource-names.html'
  - guideline_id: paypal-api-style-guide
    guideline_title: API Style Guide
    guideline_type: github
    guideline_url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
    guideline_company: PayPal
    guideline_companyLogoUrl: /media/logos/paypal.png
    guideline_companyUrl: 'https://developer.paypal.com/'
    guideline_date: 2016-08-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/paypal-api-style-guide
      guidelineTopics:
        href: /design/guidelines/paypal-api-style-guide/topics
    references:
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        quote: Collection resource names should be plural nouns
  - guideline_id: white-house-web-api-standards
    guideline_title: White House Web API Standards
    guideline_type: github
    guideline_url: 'https://github.com/WhiteHouse/api-standards'
    guideline_company: White House
    guideline_companyLogoUrl: /media/logos/whitehouse.png
    guideline_companyUrl: 'https://www.whitehouse.gov/developers'
    guideline_date: 2015-02-24T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/white-house-web-api-standards
      guidelineTopics:
        href: /design/guidelines/white-house-web-api-standards/topics
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - guideline_id: zalando-restful-api-guidelines
    guideline_title: RESTFul API Guidelines
    guideline_type: website
    guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
    guideline_company: Zalando
    guideline_companyLogoUrl: /media/logos/zalando.png
    guideline_companyUrl: 'https://tech.zalando.de/'
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-08-28T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/zalando-restful-api-guidelines
      guidelineTopics:
        href: /design/guidelines/zalando-restful-api-guidelines/topics
    references:
      - name: Property naming
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-naming'
      - name: API Naming
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html'
      - name: Use Domain-Specific Resource Names
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#must-use-domainspecific-resource-names'
---