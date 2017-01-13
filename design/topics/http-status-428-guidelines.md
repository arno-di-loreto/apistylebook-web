---
layout: topic
title: 428 Precondition Required
permalink: /design/topics/http-status-428
sort: HTTP Status User Error_428 Precondition Required
topic_id: http-status-428
topic_category: HTTP Status User Error
topic_name: 428 Precondition Required
topic_description: |
  The origin server requires the request to be conditional. 
  Intended to prevent the *lost update* problem, where a client GETs a resource's state, modifies it, 
  and PUTs it back to the server, when meanwhile a third party has modified the state on the server, 
  leading to a conflict.
guidelines:
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
---