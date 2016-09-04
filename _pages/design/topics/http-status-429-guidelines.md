---
layout: topic
title: HTTP Status 429
permalink: /design/topics/http-status-429
sort: HTTP Status_HTTP Status 429
topic_id: http-status-429
topic_category: HTTP Status
topic_name: HTTP Status 429
topic_description: When to use HTTP status 429
guidelines:
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
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
      - name: Use 429 with Headers for Rate Limits
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
---