---
layout: topic
title: Asynchronicity
permalink: /design/topics/asynchronicity
sort: Asynchronicity_Asynchronicity
topic_id: asynchronicity
topic_category: Asynchronicity
topic_name: Asynchronicity
topic_description: How to handle long operations
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
      - name: Asynchronicity
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#asynchronicity'
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
      - name: Long running API faults
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#55-long-running-api-faults'
      - name: Long running operations
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#13-long-running-operations'
      - name: Operations resource
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1324-operations-resource'
      - name: Operation resource
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1325----operation-resource'
      - name: Operation tombstones
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1326-operation-tombstones'
      - name: 'The typical flow, polling'
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1327-the-typical-flow-polling'
      - name: 'The typical flow, push notifications'
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1328-the-typical-flow-push-notifications'
      - name: Retry-After
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1329-retry-after'
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
      - name: Asynchronous Requests
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#asynchronous-requests'
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
      - name: Events
        url: 'http://zalando.github.io/restful-api-guidelines/events/events.html'
---