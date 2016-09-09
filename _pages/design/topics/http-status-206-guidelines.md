---
layout: topic
title: 206 Partial Content
permalink: /design/topics/http-status-206
sort: HTTP Status Success_206 Partial Content
topic_id: http-status-206
topic_category: HTTP Status Success
topic_name: 206 Partial Content
topic_description: |
  The server is delivering only part of the resource (byte serving) due to a range header sent by the client. The range header is used by HTTP clients to enable resuming of interrupted downloads, or split a download into multiple simultaneous streams.
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
---