---
layout: guideline
title: Atlassian REST API Policy
permalink: /design/guidelines/atlassian-rest-api-policy
sort: Atlassian_Atlassian REST API Policy
guideline_id: atlassian-rest-api-policy
guideline_title: Atlassian REST API Policy
guideline_type: website
guideline_url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy'
guideline_company: Atlassian
guideline_companyLogoUrl: /media/logos/atlassian.png
guideline_companyUrl: 'https://developer.atlassian.com/'
guideline_date: 2015-01-15T00:00:00.000Z
guideline_reviewDate: 2016-09-01T00:00:00.000Z
topics:
  - topic_id: collection-pagination
    topic_category: Collection Resources
    topic_name: Pagination
    topic_description: How to retrieve a range of resources in a collection
    topic__links:
      self:
        href: /design/topics/collection-pagination
      topicGuidelines:
        href: /design/topics/collection-pagination/guidelines
    references:
      - name: Resource/rate limits and paging
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Resource/ratelimitsandpaging'
  - topic_id: data-format
    topic_category: Data
    topic_name: Data format
    topic_description: which data format use
    topic__links:
      self:
        href: /design/topics/data-format
      topicGuidelines:
        href: /design/topics/data-format/guidelines
    references:
      - name: Compatibility policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
      - name: Structured representations (application/json)
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Structuredrepresentations(application/json)'
      - name: Forward compatibility
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Forwardcompatibility'
  - topic_id: developer-experience
    topic_category: Miscellaneous
    topic_name: Developer experience
    topic_description: How to take care of developer experience (DX)
    topic__links:
      self:
        href: /design/topics/developer-experience
      topicGuidelines:
        href: /design/topics/developer-experience/guidelines
    references:
      - name: Deprecation policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Deprecationpolicy'
  - topic_id: governance
    topic_category: API Lifecycle
    topic_name: Governance
    topic_description: 'How to ensure API governance (advertise, consistency, ...)'
    topic__links:
      self:
        href: /design/topics/governance
      topicGuidelines:
        href: /design/topics/governance/guidelines
    references:
      - name: Compatibility policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
      - name: Deprecation policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Deprecationpolicy'
  - topic_id: http-headers
    topic_category: HTTP Protocol
    topic_name: HTTP Headers
    topic_description: How to use standard or custom HTTP headers
    topic__links:
      self:
        href: /design/topics/http-headers
      topicGuidelines:
        href: /design/topics/http-headers/guidelines
    references:
      - name: Detectability (Deprecation Policy)
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Detectability'
  - topic_id: rate-limiting
    topic_category: Miscellaneous
    topic_name: Rate limiting
    topic_description: How to provide information about how many calls a consumer can do
    topic__links:
      self:
        href: /design/topics/rate-limiting
      topicGuidelines:
        href: /design/topics/rate-limiting/guidelines
    references:
      - name: Resource/rate limits and paging
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Resource/ratelimitsandpaging'
  - topic_id: resource-url-format
    topic_category: Resources
    topic_name: URL format
    topic_description: How to design URLs
    topic__links:
      self:
        href: /design/topics/resource-url-format
      topicGuidelines:
        href: /design/topics/resource-url-format/guidelines
    references:
      - name: Stable URIs
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-StableURIs'
  - topic_id: versioning
    topic_category: API Lifecycle
    topic_name: Versionning
    topic_description: How to handle API versionning
    topic__links:
      self:
        href: /design/topics/versioning
      topicGuidelines:
        href: /design/topics/versioning/guidelines
    references:
      - name: Compatibility policy
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
      - name: Backwards compatibility
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Backwardscompatibility'
      - name: Structured representations (application/json)
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Structuredrepresentations(application/json)'
      - name: API versioning
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-APIversioning'
---