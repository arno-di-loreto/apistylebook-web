---
layout: guideline
title: RESTFul API Guidelines
permalink: /design/guidelines/zalando-restful-api-guidelines
sort: Zalando_RESTFul API Guidelines
guideline_id: zalando-restful-api-guidelines
guideline_title: RESTFul API Guidelines
guideline_type: website
guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
guideline_company: Zalando
guideline_companyLogoUrl: /media/logos/zalando.png
guideline_companyUrl: 'https://tech.zalando.de/'
guideline_date: 2016-01-22T00:00:00.000Z
guideline_reviewDate: 2016-08-28T00:00:00.000Z
topics:
  - topic_id: api-counts
    topic_category: API Design
    topic_name: API counts
    topic_description: How many endpoints/resources in an API?
    topic__links:
      self:
        href: /design/topics/api-counts
      topicGuidelines:
        href: /design/topics/api-counts/guidelines
    references:
      - name: Limit of Resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-limit-of-resources'
        quote: a typical range of resources for a well-designed API is between 4 and 8
  - topic_id: asynchronicity
    topic_category: Asynchronicity
    topic_name: Asynchronicity
    topic_description: How to handle long operations
    topic__links:
      self:
        href: /design/topics/asynchronicity
      topicGuidelines:
        href: /design/topics/asynchronicity/guidelines
    references:
      - name: Events
        url: 'http://zalando.github.io/restful-api-guidelines/events/events.html'
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
      - name: Use Conventional Query Strings
        quote: q — default query parameter
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
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
      - name: Use Conventional Query Strings
        quote: 'limit, cursor, offset'
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
      - name: Pagination
        url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html'
  - topic_id: collection-retrieve
    topic_category: Collection Resources
    topic_name: Retrieve a collection
    topic_description: How to get a collection or resources
    topic__links:
      self:
        href: /design/topics/collection-retrieve
      topicGuidelines:
        href: /design/topics/collection-retrieve/guidelines
    references:
      - name: GET
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
        quote: reads a resource or set of resource instances
  - topic_id: collection-sorting
    topic_category: Collection Resources
    topic_name: Sorting a collection
    topic_description: How to sort a collection of resources
    topic__links:
      self:
        href: /design/topics/collection-sorting
      topicGuidelines:
        href: /design/topics/collection-sorting/guidelines
    references:
      - name: Use Conventional Query Strings
        quote: sort — comma-separated list of fields to sort
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
  - topic_id: collection
    topic_category: Collection Resources
    topic_name: Collection
    topic_description: What is a collection (set) of resources
    topic__links:
      self:
        href: /design/topics/collection
      topicGuidelines:
        href: /design/topics/collection/guidelines
    references:
      - name: Resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html'
  - topic_id: data-standards
    topic_category: Data
    topic_name: Standards data
    topic_description: 'Which standard use for values like languages, countries, currencies, ...'
    topic__links:
      self:
        href: /design/topics/data-standards
      topicGuidelines:
        href: /design/topics/data-standards/guidelines
    references:
      - name: 'Standards could be used for Language, Country and Currency'
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-standards-could-be-used-for-language-country-and-currency'
      - name: 'Use Standards for Country, Language and Currency Codes'
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-standards-for-country-language-and-currency-codes'
  - topic_id: data-format-date-time
    topic_category: Data
    topic_name: Date and Time
    topic_description: How to deal with date and time data
    topic__links:
      self:
        href: /design/topics/data-format-date-time
      topicGuidelines:
        href: /design/topics/data-format-date-time/guidelines
    references:
      - name: Date property values should conform to RFC 3399
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
      - name: Time durations and intervals could conform to ISO 8601
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
      - name: Use Standard Date and Time Formats
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#must-use-standard-date-and-time-formats'
      - name: HTTP headers
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
        quote: Use the HTTP date format defined in RFC 7231
  - topic_id: data-format-null
    topic_category: Data
    topic_name: Null data
    topic_description: How to deal with null data
    topic__links:
      self:
        href: /design/topics/data-format-null
      topicGuidelines:
        href: /design/topics/data-format-null/guidelines
    references:
      - name: Property values
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
      - name: Null values should have their fields removed
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-null-values-should-have-their-fields-removed'
      - name: Boolean property values must not be null
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#must-boolean-property-values-must-not-be-null'
      - name: Empty array values should not be null
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-empty-array-values-should-not-be-null'
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
      - name: Property Values
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
      - name: Date property values should conform to RFC 3399
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
      - name: Time durations and intervals could conform to ISO 8601
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
      - name: Data Formats
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html'
      - name: Common Data Objects
        url: 'http://zalando.github.io/restful-api-guidelines/common-data-objects/CommonDataObjects.html'
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
      - name: Provide External Documentation
        url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#should-provide-external-documentation'
      - name: Reflect Deprecation in API Definition
        url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html#must-reflect-deprecation-in-api-definition'
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
      - name: Design Principles
        url: 'http://zalando.github.io/restful-api-guidelines/design-principles/DesignPrinciples.html'
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
      - name: API First
        url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#must-api-first-define-apis-using-openapi'
      - name: Deprecation
        url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html'
      - name: API Discovery
        url: 'http://zalando.github.io/restful-api-guidelines/api-discovery/ApiDiscovery.html'
  - topic_id: http-caching
    topic_category: HTTP Protocol
    topic_name: Caching
    topic_description: How to use and provide relevant caching informations
    topic__links:
      self:
        href: /design/topics/http-caching
      topicGuidelines:
        href: /design/topics/http-caching/guidelines
    references:
      - name: Support the ETag Header
        url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html#could-support-the-etag-header'
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
      - name: Use Media Type Versioning
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-use-media-type-versioning'
      - name: Modify the Content-Type for Embedded Resources
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
      - name: Use Application-Specific Content Types
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-applicationspecific-content-types'
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
      - name: You Must Hyphenate HTTP Headers
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-you-must-hyphenate-http-headers'
      - name: Prefer Hyphenated-Pascal-Case for HTTP header Fields
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#should-prefer-hyphenatedpascalcase-for-http-header-fields'
      - name: Use Standardized Headers
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-standardized-headers'
      - name: Use 429 with Headers for Rate Limits
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
      - name: HTTP headers
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
        quote: Use the HTTP date format defined in RFC 7231
      - name: Common Headers
        url: 'http://zalando.github.io/restful-api-guidelines/headers/CommonHeaders.html'
      - name: Proprietary Headers
        url: 'http://zalando.github.io/restful-api-guidelines/headers/ProprietaryHeaders.html'
      - name: Add a Warning Header to Responses
        url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html#should-add-a-warning-header-to-responses'
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
      - name: Success Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
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
      - name: Success Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
  - topic_id: http-status-202
    topic_category: HTTP Status
    topic_name: HTTP Status 202
    topic_description: When to use HTTP status 202
    topic__links:
      self:
        href: /design/topics/http-status-202
      topicGuidelines:
        href: /design/topics/http-status-202/guidelines
    references:
      - name: Success Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
  - topic_id: http-status-204
    topic_category: HTTP Status
    topic_name: HTTP Status 204
    topic_description: When to use HTTP status 204
    topic__links:
      self:
        href: /design/topics/http-status-204
      topicGuidelines:
        href: /design/topics/http-status-204/guidelines
    references:
      - name: Success Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
  - topic_id: http-status-301
    topic_category: HTTP Status
    topic_name: HTTP Status 301
    topic_description: When to use HTTP status 301
    topic__links:
      self:
        href: /design/topics/http-status-301
      topicGuidelines:
        href: /design/topics/http-status-301/guidelines
    references:
      - name: Redirection Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
  - topic_id: http-status-302
    topic_category: HTTP Status
    topic_name: HTTP Status 302
    topic_description: When to use HTTP status 302
    topic__links:
      self:
        href: /design/topics/http-status-302
      topicGuidelines:
        href: /design/topics/http-status-302/guidelines
    references:
      name: HTTP Status 302
      description: When to use HTTP status 302
  - topic_id: http-status-303
    topic_category: HTTP Status
    topic_name: HTTP Status 303
    topic_description: When to use HTTP status 303
    topic__links:
      self:
        href: /design/topics/http-status-303
      topicGuidelines:
        href: /design/topics/http-status-303/guidelines
    references:
      - name: Redirection Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
  - topic_id: http-status-304
    topic_category: HTTP Status
    topic_name: HTTP Status 304
    topic_description: When to use HTTP status 304
    topic__links:
      self:
        href: /design/topics/http-status-304
      topicGuidelines:
        href: /design/topics/http-status-304/guidelines
    references:
      - name: Redirection Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
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
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-401
    topic_category: HTTP Status
    topic_name: HTTP Status 401
    topic_description: When to use HTTP status 401
    topic__links:
      self:
        href: /design/topics/http-status-401
      topicGuidelines:
        href: /design/topics/http-status-401/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-403
    topic_category: HTTP Status
    topic_name: HTTP Status 403
    topic_description: When to use HTTP status 403
    topic__links:
      self:
        href: /design/topics/http-status-403
      topicGuidelines:
        href: /design/topics/http-status-403/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-406
    topic_category: HTTP Status
    topic_name: HTTP Status 406
    topic_description: When to use HTTP status 406
    topic__links:
      self:
        href: /design/topics/http-status-406
      topicGuidelines:
        href: /design/topics/http-status-406/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-408
    topic_category: HTTP Status
    topic_name: HTTP Status 408
    topic_description: When to use HTTP status 408
    topic__links:
      self:
        href: /design/topics/http-status-408
      topicGuidelines:
        href: /design/topics/http-status-408/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-409
    topic_category: HTTP Status
    topic_name: HTTP Status 409
    topic_description: When to use HTTP status 409
    topic__links:
      self:
        href: /design/topics/http-status-409
      topicGuidelines:
        href: /design/topics/http-status-409/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-412
    topic_category: HTTP Status
    topic_name: HTTP Status 412
    topic_description: When to use HTTP status 412
    topic__links:
      self:
        href: /design/topics/http-status-412
      topicGuidelines:
        href: /design/topics/http-status-412/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-415
    topic_category: HTTP Status
    topic_name: HTTP Status 415
    topic_description: When to use HTTP status 415
    topic__links:
      self:
        href: /design/topics/http-status-415
      topicGuidelines:
        href: /design/topics/http-status-415/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-423
    topic_category: HTTP Status
    topic_name: HTTP Status 423
    topic_description: When to use HTTP status 423
    topic__links:
      self:
        href: /design/topics/http-status-423
      topicGuidelines:
        href: /design/topics/http-status-423/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-428
    topic_category: HTTP Status
    topic_name: HTTP Status 428
    topic_description: When to use HTTP status 428
    topic__links:
      self:
        href: /design/topics/http-status-428
      topicGuidelines:
        href: /design/topics/http-status-428/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
  - topic_id: http-status-429
    topic_category: HTTP Status
    topic_name: HTTP Status 429
    topic_description: When to use HTTP status 429
    topic__links:
      self:
        href: /design/topics/http-status-429
      topicGuidelines:
        href: /design/topics/http-status-429/guidelines
    references:
      - name: Client Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
      - name: Use 429 with Headers for Rate Limits
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
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
      - name: Server Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
  - topic_id: http-status-501
    topic_category: HTTP Status
    topic_name: HTTP Status 501
    topic_description: When to use HTTP status 501
    topic__links:
      self:
        href: /design/topics/http-status-501
      topicGuidelines:
        href: /design/topics/http-status-501/guidelines
    references:
      - name: Server Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
  - topic_id: http-status-503
    topic_category: HTTP Status
    topic_name: HTTP Status 503
    topic_description: When to use HTTP status 503
    topic__links:
      self:
        href: /design/topics/http-status-503
      topicGuidelines:
        href: /design/topics/http-status-503/guidelines
    references:
      - name: Server Side Error Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
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
      - name: Providing Error Documentation
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-providing-error-documentation'
      - name: Use Problem JSON
        url: 'http://zalando.github.io/restful-api-guidelines/common-data-objects/CommonDataObjects.html#must-use-problem-json'
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
      - name: Use Meaningful HTTP Status Codes
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-meaningful-http-status-codes'
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
      - name: DELETE
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#delete'
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
      - name: GET
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
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
      - name: HEAD
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#head'
  - topic_id: http-methods-options
    topic_category: HTTP Methods
    topic_name: OPTIONS
    topic_description: When to use HTTP method OPTION
    topic__links:
      self:
        href: /design/topics/http-methods-options
      topicGuidelines:
        href: /design/topics/http-methods-options/guidelines
    references:
      - name: OPTIONS
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#options'
  - topic_id: http-methods-patch
    topic_category: HTTP Methods
    topic_name: PATCH
    topic_description: When to use HTTP method PATCH
    topic__links:
      self:
        href: /design/topics/http-methods-patch
      topicGuidelines:
        href: /design/topics/http-methods-patch/guidelines
    references:
      - name: PATCH
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
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
      - name: POST
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#post'
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
      - name: PUT
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
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
      - name: Use HTTP Methods Correctly
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-http-methods-correctly'
      - name: HTTP Methods must Fulfill Safeness and Idempotency Properties
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must--http-methods-must-fulfill-safeness-and-idempotency-properties'
  - topic_id: http
    topic_category: HTTP Protocol
    topic_name: HTTP protocol
    topic_description: General informations about HTTP protocol
    topic__links:
      self:
        href: /design/topics/http
      topicGuidelines:
        href: /design/topics/http/guidelines
    references:
      - name: HTTP
        description: 'http://zalando.github.io/restful-api-guidelines/http/Http.html'
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
      - name: Use Pagination Links Where Applicable
        url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html#could-use-pagination-links-where-applicable'
      - name: Use a well-defined subset of HAL
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
      - name: Use Custom Link Relations
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#could-use-custom-link-relations'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
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
      - name: Use Pagination Links Where Applicable
        url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html#could-use-pagination-links-where-applicable'
      - name: Hypermedia
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html'
      - name: Use a well-defined subset of HAL
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
  - topic_id: naming-language
    topic_category: Naming
    topic_name: Language
    topic_description: Which language(s) use when designing an API
    topic__links:
      self:
        href: /design/topics/naming-language
      topicGuidelines:
        href: /design/topics/naming-language/guidelines
    references:
      - name: Write APIs in U.S. English
        url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#must-write-apis-in-us-english'
  - topic_id: naming-case
    topic_category: Naming
    topic_name: Case
    topic_description: 'Which case (lowercase, camelCase, ...) to use and when'
    topic__links:
      self:
        href: /design/topics/naming-case
      topicGuidelines:
        href: /design/topics/naming-case/guidelines
    references:
      - name: Property names must be snake_case
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#must-property-names-must-be-snakecase-and-never-camelcase'
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
      - name: Property naming
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-naming'
      - name: API Naming
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html'
      - name: Use Domain-Specific Resource Names
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#must-use-domainspecific-resource-names'
  - topic_id: notifications-server-events
    topic_category: Asynchronicity
    topic_name: Notifying API consumers
    topic_description: How to send events or notifications to API consumers
    topic__links:
      self:
        href: /design/topics/notifications-server-events
      topicGuidelines:
        href: /design/topics/notifications-server-events/guidelines
    references:
      - name: Events
        url: 'http://zalando.github.io/restful-api-guidelines/events/events.html'
  - topic_id: performance
    topic_category: Miscellaneous
    topic_name: Performance and bandwidth
    topic_description: How to deal with high traffic or consumers with low bandwith
    topic__links:
      self:
        href: /design/topics/performance
      topicGuidelines:
        href: /design/topics/performance/guidelines
    references:
      name: Performance
      url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html'
  - topic_id: query-parameter
    topic_category: Miscellaneous
    topic_name: Query parameters
    topic_description: How to use query parameters
    topic__links:
      self:
        href: /design/topics/query-parameter
      topicGuidelines:
        href: /design/topics/query-parameter/guidelines
    references:
      - name: Query parameters must be snake_case (never camelCase)
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-query-parameters-must-be-snakecase-never-camelcase'
      - name: Use Conventional Query Strings
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
  - topic_id: resource-action
    topic_category: Resources
    topic_name: Action resource
    topic_description: How to use action resource (e.g. resources like /cancel or /approve)
    topic__links:
      self:
        href: /design/topics/resource-action
      topicGuidelines:
        href: /design/topics/resource-action/guidelines
    references:
      - name: Avoid Actions — Think About Resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#must-avoid-actions-—-think-about-resources'
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
      - name: POST
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#post'
        quote: creates a resource instance
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
      - name: DELETE
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#delete'
        quote: deletes a resource instance
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
      - name: Use a well-defined subset of HAL
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
      - name: Use Custom Link Relations
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#could-use-custom-link-relations'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
  - topic_id: resource-replacement
    topic_category: Resources
    topic_name: Replace resource
    topic_description: How to replace (or update fully) a resource
    topic__links:
      self:
        href: /design/topics/resource-replacement
      topicGuidelines:
        href: /design/topics/resource-replacement/guidelines
    references:
      - name: PUT
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
        quote: fully uploads an entity
  - topic_id: resource-retrieve-dereference
    topic_category: Resources
    topic_name: Dereference Relationships
    topic_description: How to load a resource and its linked resources in one call
    topic__links:
      self:
        href: /design/topics/resource-retrieve-dereference
      topicGuidelines:
        href: /design/topics/resource-retrieve-dereference/guidelines
    references:
      - name: Use Conventional Query Strings
        quote: embed — to expand embedded entities
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
      - name: Define useful resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
      - name: Allow Optional Embedding of Sub-Resources
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#should-allow-optional-embedding-of-subresources'
      - name: Modify the Content-Type for Embedded Resources
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
  - topic_id: resource-retrieve-partial
    topic_category: Resources
    topic_name: Retrieve resource partially
    topic_description: How to retrieve partially a resource
    topic__links:
      self:
        href: /design/topics/resource-retrieve-partial
      topicGuidelines:
        href: /design/topics/resource-retrieve-partial/guidelines
    references:
      - name: Use Conventional Query Strings
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
        quote: fields — to retrieve a subset of fields
      - name: Define useful resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
      - name: Support Filtering of Resource Fields
        url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html#should-support-filtering-of-resource-fields'
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
      - name: GET
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
        quote: reads a resource or set of resource instances
  - topic_id: resource-update-partial
    topic_category: Resources
    topic_name: Update resource partially
    topic_description: How to udate partially a resource
    topic__links:
      self:
        href: /design/topics/resource-update-partial
      topicGuidelines:
        href: /design/topics/resource-update-partial/guidelines
    references:
      - name: PATCH
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
        quote: only a specific subset of resource fields are replaced
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
      - name: PUT
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
      - name: PATCH
        url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
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
      - name: Path segments must be lowercase separate words with hyphens
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-path-segments-must-be-lowercase-separate-words-with-hyphens'
      - name: Always Pluralize Resource Names
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-always-pluralize-resource-names'
      - name: First Path segment May be /api
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-first-path-segment-may-be-api'
      - name: Avoid Trailing Slashes
        url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-avoid-trailing-slashes'
      - name: Limit of Sub-Resource Levels
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-limit-of-subresource-levels'
  - topic_id: resource
    topic_category: Resources
    topic_name: Resource
    topic_description: General informations about resources
    topic__links:
      self:
        href: /design/topics/resource
      topicGuidelines:
        href: /design/topics/resource/guidelines
    references:
      - name: resources
        url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html'
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
      - name: Security
        url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html'
      - name: Secure Endpoints with OAuth 2.0
        url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html#must-secure-endpoints-with-oauth-20'
      - name: Define and Assign Access Rights (Scopes)
        url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html#must-define-and-assign-access-rights-scopes'
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
      - name: Compatibility
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html'
      - name: Don’t Break Backward Compatibility
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-dont-break-backward-compatibility'
      - name: Avoid Versioning
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#should-avoid-versioning'
      - name: Use Media Type Versioning
        url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-use-media-type-versioning'
---