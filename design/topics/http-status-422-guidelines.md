---
layout: topic
title: 422 Unprocessable Entity
permalink: /design/topics/http-status-422
sort: HTTP Status User Error_422 Unprocessable Entity
topic_id: http-status-422
topic_category: HTTP Status User Error
topic_name: 422 Unprocessable Entity
topic_description: The request was well-formed but was unable to be followed due to semantic errors.
guidelines:
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: HTTP Status (Update Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
      - name: HTTP Status (Update Partial Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
---