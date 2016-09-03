---
layout: guideline
title: White House Web API Standards
permalink: /design/guidelines/white-house-web-api-standards
sort: White House_White House Web API Standards
guideline_id: white-house-web-api-standards
guideline_title: White House Web API Standards
guideline_type: github
guideline_url: 'https://github.com/WhiteHouse/api-standards'
guideline_company: White House
guideline_companyLogoUrl: /media/logos/whitehouse.png
guideline_companyUrl: 'https://www.whitehouse.gov/developers'
guideline_date: 2015-02-24T00:00:00.000Z
guideline_reviewDate: 2016-08-18T00:00:00.000Z
topics:
  - topic_id: collection-filtering
    topic_category: Collection Resources
    topic_name: Filtering
    topic_description: How to select some resources in a collection
    topic__links:
      self:
        href: /design/topics/collection-filtering
      topicGuidelines:
        href: /design/topics/collection-filtering/guidelines
    references:
      - name: Record Limits
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#record-limits'
  - topic_id: cors
    topic_category: Miscellaneous
    topic_name: CORS
    topic_description: How to deal with CORS
    topic__links:
      self:
        href: /design/topics/cors
      topicGuidelines:
        href: /design/topics/cors/guidelines
    references:
      - name: JSONP
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#jsonp'
  - topic_id: http-content-negotiation
    topic_category: HTTP Protocol
    topic_name: Content negociation and media types
    topic_description: 'How to describe your API data format and/or propose different formats (like json, yaml, xml atom, ...)'
    topic__links:
      self:
        href: /design/topics/http-content-negotiation
      topicGuidelines:
        href: /design/topics/http-content-negotiation/guidelines
    references:
      - name: General guidelines for RESTful URLs
        quote: 'Formats should be in the form of api/v2/resource/{id}.json'
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
      - name: General guidelines for RESTful URLs
        quote: URL v. header
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: http-status-200
    topic_category: HTTP Status
    topic_name: HTTP Status 200
    topic_description: When to use HTTP status 200
    topic__links:
      self:
        href: /design/topics/http-status-200
      topicGuidelines:
        href: /design/topics/http-status-200/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
  - topic_id: http-status-400
    topic_category: HTTP Status
    topic_name: HTTP Status 400
    topic_description: When to use HTTP status 400
    topic__links:
      self:
        href: /design/topics/http-status-400
      topicGuidelines:
        href: /design/topics/http-status-400/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
  - topic_id: http-status-500
    topic_category: HTTP Status
    topic_name: HTTP Status 500
    topic_description: When to use HTTP status 500
    topic__links:
      self:
        href: /design/topics/http-status-500
      topicGuidelines:
        href: /design/topics/http-status-500/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
  - topic_id: http-status-standard-error
    topic_category: Error handling
    topic_name: Error format
    topic_description: How to provide information about errors
    topic__links:
      self:
        href: /design/topics/http-status-standard-error
      topicGuidelines:
        href: /design/topics/http-status-standard-error/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
  - topic_id: http-status
    topic_category: HTTP Status
    topic_name: HTTP Statuses
    topic_description: General information about HTTP statuses usage
    topic__links:
      self:
        href: /design/topics/http-status
      topicGuidelines:
        href: /design/topics/http-status/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
  - topic_id: http-methods-delete
    topic_category: HTTP Methods
    topic_name: DELETE
    topic_description: When to use HTTP method DELETE
    topic__links:
      self:
        href: /design/topics/http-methods-delete
      topicGuidelines:
        href: /design/topics/http-methods-delete/guidelines
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: http-methods-get
    topic_category: HTTP Methods
    topic_name: GET
    topic_description: When to use HTTP method GET
    topic__links:
      self:
        href: /design/topics/http-methods-get
      topicGuidelines:
        href: /design/topics/http-methods-get/guidelines
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: http-methods-post
    topic_category: HTTP Methods
    topic_name: POST
    topic_description: When to use HTTP method POST
    topic__links:
      self:
        href: /design/topics/http-methods-post
      topicGuidelines:
        href: /design/topics/http-methods-post/guidelines
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: http-methods-put
    topic_category: HTTP Methods
    topic_name: PUT
    topic_description: When to use HTTP method PUT
    topic__links:
      self:
        href: /design/topics/http-methods-put
      topicGuidelines:
        href: /design/topics/http-methods-put/guidelines
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: http-methods
    topic_category: HTTP Methods
    topic_name: HTTP methods
    topic_description: General information about HTTP methods usage
    topic__links:
      self:
        href: /design/topics/http-methods
      topicGuidelines:
        href: /design/topics/http-methods/guidelines
    references:
      - name: HTTP verbs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: naming
    topic_category: Naming
    topic_name: Naming
    topic_description: How to name things
    topic__links:
      self:
        href: /design/topics/naming
      topicGuidelines:
        href: /design/topics/naming/guidelines
    references:
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
  - topic_id: resource-creation
    topic_category: Resources
    topic_name: Create resource
    topic_description: How to create resources
    topic__links:
      self:
        href: /design/topics/resource-creation
      topicGuidelines:
        href: /design/topics/resource-creation/guidelines
    references:
      - name: HTTP verbs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
  - topic_id: resource-deletion
    topic_category: Resources
    topic_name: Delete resource
    topic_description: How to delete resources
    topic__links:
      self:
        href: /design/topics/resource-deletion
      topicGuidelines:
        href: /design/topics/resource-deletion/guidelines
    references:
      - name: HTTP verbs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
  - topic_id: resource-multiple
    topic_category: Resources
    topic_name: Batch Bulk
    topic_description: How to handle batch/bulk processing/creation/update/... (e.g. handle multiple resources at conce)
    topic__links:
      self:
        href: /design/topics/resource-multiple
      topicGuidelines:
        href: /design/topics/resource-multiple/guidelines
    references:
      - name: HTTP verbs
        quote: 'Bulk update, Delete all dogs'
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
  - topic_id: resource-retrieve
    topic_category: Resources
    topic_name: Retrieve resource
    topic_description: How to retrieve a resource
    topic__links:
      self:
        href: /design/topics/resource-retrieve
      topicGuidelines:
        href: /design/topics/resource-retrieve/guidelines
    references:
      - name: HTTP verbs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
  - topic_id: resource-update
    topic_category: Resources
    topic_name: Update resource
    topic_description: How to update a resource
    topic__links:
      self:
        href: /design/topics/resource-update
      topicGuidelines:
        href: /design/topics/resource-update/guidelines
    references:
      - name: HTTP verbs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
      - name: RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#restful-urls'
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
      - name: General guidelines for RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
      - name: Versions
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#versions'
---