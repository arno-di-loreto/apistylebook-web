---
layout: topic
title: HTTP Status 404
permalink: /design/topics/http-status-404
sort: HTTP Status_HTTP Status 404
topic_id: http-status-404
topic_category: HTTP Status
topic_name: HTTP Status 404
topic_description: When to use HTTP status 404
guidelines:
  - guideline_id: atlassian-rest-api-design-guidelines-version-1
    guideline_title: Atlassian REST API Design Guidelines version 1
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1/topics
    references:
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
  - guideline_id: ausdto-api-design-guide
    guideline_title: API Design Guide
    guideline_type: website
    guideline_url: 'https://apiguide.readthedocs.io/en/latest/index.html'
    guideline_company: Australian Digital Transformation Office
    guideline_companyLogoUrl: /media/logos/ausdto.png
    guideline_companyUrl: 'https://www.dto.gov.au/'
    guideline_date: 2015-10-20T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/ausdto-api-design-guide
      guidelineTopics:
        href: /design/guidelines/ausdto-api-design-guide/topics
    references:
      - name: GET /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: HTTP Status (Get List of resources)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-1'
      - name: Delete Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
        quote: 404 Not Found HTTP status should not be utilized
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
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
      - name: HTTP Status (Collections)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
      - name: Delete Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
---