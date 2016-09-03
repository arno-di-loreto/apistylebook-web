---
layout: topic
title: Null data
permalink: /design/topics/data-format-null
sort: Data_Null data
topic_id: data-format-null
topic_category: Data
topic_name: Null data
topic_description: How to deal with null data
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
      - name: JSON Attributes
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#json-attributes'
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
      - name: Property values
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
      - name: Null values should have their fields removed
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-null-values-should-have-their-fields-removed'
      - name: Boolean property values must not be null
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#must-boolean-property-values-must-not-be-null'
      - name: Empty array values should not be null
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-empty-array-values-should-not-be-null'
---