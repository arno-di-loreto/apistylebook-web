---
layout: guideline
title: API Design Guide
permalink: /design/guidelines/ausdto-api-design-guide
sort: Australian Digital Transformation Office_API Design Guide
guideline_id: ausdto-api-design-guide
guideline_title: API Design Guide
guideline_type: website
guideline_url: 'https://apiguide.readthedocs.io/en/latest/index.html'
guideline_company: Australian Digital Transformation Office
guideline_companyLogoUrl: /media/logos/ausdto.png
guideline_companyUrl: 'https://www.dto.gov.au/'
guideline_date: 2015-10-20T00:00:00.000Z
guideline_reviewDate: 2016-08-18T00:00:00.000Z
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
      - name: Batching results
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/batching_results.html'
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
      - name: Support cross-domain mashups with CORS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/cors.html'
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
      - name: Empathy
        url: 'https://apiguide.readthedocs.io/en/latest/principles/empathy.html'
      - name: Errors
        url: 'https://apiguide.readthedocs.io/en/latest/principles/errors.html'
      - name: Endpoint Stability
        url: 'https://apiguide.readthedocs.io/en/latest/principles/availability.html'
  - topic_id: documentation
    topic_category: Miscellaneous
    topic_name: Documentation
    topic_description: How to produce and/or propose API documentation
    topic__links:
      self:
        href: /design/topics/documentation
      topicGuidelines:
        href: /design/topics/documentation/guidelines
    references:
      - name: Discoverability
        url: 'https://apiguide.readthedocs.io/en/latest/principles/discoverability.html'
      - name: Document your API
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/documentation.html'
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
      - name: Register your API
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/advertise.html'
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
      - name: Formats
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#formats'
      - name: API Payload format encoding
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#api-payload-format-encoding'
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
      - name: GET /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
      - name: PUT /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines'
      - name: DELETE /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines'
      - name: DELETE /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines-1234'
      - name: HEAD /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines'
      - name: HEAD /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines-1234'
  - topic_id: http-status-201
    topic_category: HTTP Status
    topic_name: HTTP Status 201
    topic_description: When to use HTTP status 201
    topic__links:
      self:
        href: /design/topics/http-status-201
      topicGuidelines:
        href: /design/topics/http-status-201/guidelines
    references:
      - name: Use HTTP methods and status codes
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
      - name: PUT /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines-1234'
  - topic_id: http-status-404
    topic_category: HTTP Status
    topic_name: HTTP Status 404
    topic_description: When to use HTTP status 404
    topic__links:
      self:
        href: /design/topics/http-status-404
      topicGuidelines:
        href: /design/topics/http-status-404/guidelines
    references:
      - name: GET /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
  - topic_id: http-status-405
    topic_category: HTTP Status
    topic_name: HTTP Status 405
    topic_description: When to use HTTP status 405
    topic__links:
      self:
        href: /design/topics/http-status-405
      topicGuidelines:
        href: /design/topics/http-status-405/guidelines
    references:
      - name: Use HTTP methods and status codes
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
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
      - name: HTTP response principles
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#http-response-principles'
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
      - name: DELETE /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines'
      - name: DELETE /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines-1234'
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
      - name: GET /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
  - topic_id: http-methods-head
    topic_category: HTTP Methods
    topic_name: HEAD
    topic_description: When to use HTTP method HEAD
    topic__links:
      self:
        href: /design/topics/http-methods-head
      topicGuidelines:
        href: /design/topics/http-methods-head/guidelines
    references:
      - name: HEAD /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines'
      - name: HEAD /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines-1234'
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
      - name: POST /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#post--magazines'
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
      - name: PUT /magazines
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines'
      - name: PUT /magazines/1234
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines-1234'
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
      - name: Use HTTP methods and status codes
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
  - topic_id: hypermedia-read
    topic_category: Hypermedia
    topic_name: Hypermedia (read)
    topic_description: How to use hypermedia to read data
    topic__links:
      self:
        href: /design/topics/hypermedia-read
      topicGuidelines:
        href: /design/topics/hypermedia-read/guidelines
    references:
      - name: Management state with HATEOAS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
  - topic_id: hypermedia-write
    topic_category: Hypermedia
    topic_name: Hypermedia (write)
    topic_description: How to use hypermedia to write data
    topic__links:
      self:
        href: /design/topics/hypermedia-write
      topicGuidelines:
        href: /design/topics/hypermedia-write/guidelines
    references:
      - name: Management state with HATEOAS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
  - topic_id: hypermedia
    topic_category: Hypermedia
    topic_name: Hypermedia
    topic_description: How to use hypermedia
    topic__links:
      self:
        href: /design/topics/hypermedia
      topicGuidelines:
        href: /design/topics/hypermedia/guidelines
    references:
      - name: Management state with HATEOAS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
  - topic_id: global-design
    topic_category: API Design
    topic_name: Global design
    topic_description: General considerations on API design
    topic__links:
      self:
        href: /design/topics/global-design
      topicGuidelines:
        href: /design/topics/global-design/guidelines
    references:
      - name: Granularity
        url: 'https://apiguide.readthedocs.io/en/latest/principles/granularity.html'
      - name: Functionality
        url: 'https://apiguide.readthedocs.io/en/latest/principles/coverage.html'
  - topic_id: resource-relationships
    topic_category: Resources
    topic_name: Relationships
    topic_description: How to define and use relations between resources
    topic__links:
      self:
        href: /design/topics/resource-relationships
      topicGuidelines:
        href: /design/topics/resource-relationships/guidelines
    references:
      - name: Management state with HATEOAS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
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
      - name: URL Depth
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#url-depth'
      - name: Good RESTful URL examples
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#good-restful-url-examples'
  - topic_id: security
    topic_category: Security
    topic_name: Security
    topic_description: Security concerns
    topic__links:
      self:
        href: /design/topics/security
      topicGuidelines:
        href: /design/topics/security/guidelines
    references:
      - name: Privacy and security
        url: 'https://apiguide.readthedocs.io/en/latest/principles/security.html'
  - topic_id: security-data
    topic_category: Security
    topic_name: Data privacy
    topic_description: Data privacy concerns
    topic__links:
      self:
        href: /design/topics/security-data
      topicGuidelines:
        href: /design/topics/security-data/guidelines
    references:
      - name: Privacy and security
        url: 'https://apiguide.readthedocs.io/en/latest/principles/security.html'
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
      - name: Versioning
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#versioning'
      - name: Use versions
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/versioning.html'
---