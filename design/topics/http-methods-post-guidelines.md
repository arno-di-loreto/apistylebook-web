---
layout: topic
title: POST
permalink: /design/topics/http-methods-post
sort: HTTP Methods_POST
topic_id: http-methods-post
topic_category: HTTP Methods
topic_name: POST
topic_description: |
  The POST method requests that the server accept the entity enclosed in the request as a new subordinate of the web resource identified by the URI. The data POSTed might be, for example, an annotation for existing resources; a message for a bulletin board, newsgroup, mailing list, or comment thread; a block of data that is the result of submitting a web form to a data-handling process; or an item to add to a database.
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
      - name: POST /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#post--magazines'
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
    guideline__links:
      self:
        href: /design/guidelines/cisco-api-design-guide
      guidelineTopics:
        href: /design/guidelines/cisco-api-design-guide/topics
    references:
      - name: 3.6.1 POST
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
  - guideline_id: cloud-foundy-cloud-controller-api-style-guide
    guideline_title: Cloud Controller API v3 Style Guide (Proposal)
    guideline_type: github
    guideline_url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
    guideline_company: Cloud Foundry
    guideline_companyLogoUrl: /media/logos/cloudfoundry.png
    guideline_companyUrl: 'https://www.cloudfoundry.org/'
    guideline_screenshotUrl: /media/screenshots/cloud-foundy-cloud-controller-api-style-guide.png
    guideline_date: 2016-05-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
      guidelineTopics:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
    references:
      - name: POST
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#post'
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
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      - name: Create New Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource'
      - name: Using POST (Search)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/search/search.md#using-post'
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
      - name: POST
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
      - name: Changing collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
      - name: POST (Long running operations)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1322-post'
      - name: 'POST, hybrid model (Long running operations)'
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1323-post-hybrid-model'
  - guideline_id: paypal-api-style-guide
    guideline_title: API Style Guide
    guideline_type: github
    guideline_url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
    guideline_company: PayPal
    guideline_companyLogoUrl: /media/logos/paypal.png
    guideline_companyUrl: 'https://developer.paypal.com/'
    guideline_screenshotUrl: /media/screenshots/paypal-api-style-guide.png
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
      - name: Create New Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
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
      - name: POST
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#post'
---