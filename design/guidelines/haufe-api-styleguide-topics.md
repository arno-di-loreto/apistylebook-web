---
layout: guideline
title: Haufe API style guide
permalink: /design/guidelines/haufe-api-styleguide
sort: Haufe_Haufe API style guide
guideline_id: haufe-api-styleguide
guideline_title: Haufe API style guide
guideline_type: github
guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
guideline_company: Haufe
guideline_companyLogoUrl: /media/logos/haufe.png
guideline_companyUrl: 'http://dev.haufe.com/'
guideline_screenshotUrl: /media/screenshots/haufe-api-styleguide.png
guideline_date: 2015-01-15T00:00:00.000Z
guideline_reviewDate: 2016-08-31T00:00:00.000Z
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
      - name: Filtering
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#filtering'
      - name: Time selection
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#time-selection'
      - name: Search
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/search/search.md'
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
      - name: Paging
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#paging'
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
      - name: Get List of resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#get-list-of-resources'
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
      - name: Sorting
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#sorting'
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
      - name: Collection Resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md'
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
      - name: Currency
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#currency'
        quote: 3-character ISO-4217
      - name: Country
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#country'
        quote: ISO 3166-1-alpha-2
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
      - name: Dates and Times
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#dates-and-times'
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
      - name: Hypermedia Response Format
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/response-format/response-format.md'
      - name: Type Formatting
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md'
      - name: Message Schema and Postel's Law
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
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
      - name: Documentation
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/documentation/documentation.md'
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
      - name: Every API MUST be described using a formal API description language
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md#every-api-must-be-described-using-a-formal-api-description-language'
      - name: Documentation
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/documentation/documentation.md'
  - topic_id: errors
    topic_category: Error handling
    topic_name: Errors
    topic_description: How to handle errors
    topic__links:
      self:
        href: /design/topics/errors
      topicGuidelines:
        href: /design/topics/errors/guidelines
    references:
      - name: Error handling
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/error-handling/error-handling.md'
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
      - name: Introduction
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/introduction/introduction.md'
      - name: General Guidelines
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md'
      - name: Message Schema and Postel's Law
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
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
      - name: API Modelling and Design Process
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#api-modelling-and-design-process'
      - name: API Design Review Process
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-review-process/api-design-review-process.md'
      - name: Message Schema and Postel's Law
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
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
      - name: Caching
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md'
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
      - name: Expires HTTP Header
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#expires-http-header'
      - name: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
      - name: ETag
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#etag'
  - topic_id: http-status-200
    topic_category: HTTP Status Success
    topic_name: 200 OK
    topic_description: 'Standard response for successful HTTP requests. The actual response will depend on the request method used. In a GET request, the response will contain an entity corresponding to the requested resource. In a POST request, the response will contain an entity describing or containing the result of the action.'
    topic__links:
      self:
        href: /design/topics/http-status-200
      topicGuidelines:
        href: /design/topics/http-status-200/guidelines
    references:
      - name: HTTP Status (Get List of resources)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-1'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-201
    topic_category: HTTP Status Success
    topic_name: 201 Created
    topic_description: 'The request has been fulfilled, resulting in the creation of a new resource.'
    topic__links:
      self:
        href: /design/topics/http-status-201
      topicGuidelines:
        href: /design/topics/http-status-201/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-204
    topic_category: HTTP Status Success
    topic_name: 204 No Content
    topic_description: The server successfully processed the request and is not returning any content.
    topic__links:
      self:
        href: /design/topics/http-status-204
      topicGuidelines:
        href: /design/topics/http-status-204/guidelines
    references:
      - name: HTTP Status (Update Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
      - name: HTTP Status (Update Partial Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
      - name: Delete Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-304
    topic_category: HTTP Status Redirection
    topic_name: 304 Not Modified
    topic_description: |
      Indicates that the resource has not been modified since the version specified by the request headers If-Modified-Since or If-None-Match. In such case, there is no need to retransmit the resource since the client still has a previously-downloaded copy.
    topic__links:
      self:
        href: /design/topics/http-status-304
      topicGuidelines:
        href: /design/topics/http-status-304/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-400
    topic_category: HTTP Status User Error
    topic_name: 400 Bad Request
    topic_description: |
      The server cannot or will not process the request due to an apparent client error (e.g., malformed request syntax, too large size, invalid request message framing, or deceptive request routing).
    topic__links:
      self:
        href: /design/topics/http-status-400
      topicGuidelines:
        href: /design/topics/http-status-400/guidelines
    references:
      - name: HTTP Status (Get List of resources)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
      - name: HTTP Status (Update Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
      - name: HTTP Status (Update Partial Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-401
    topic_category: HTTP Status User Error
    topic_name: 401 Unauthorized
    topic_description: |
      Similar to 403 Forbidden, but specifically for use when authentication is required and has failed or has not yet been provided. The response must include a WWW-Authenticate header field containing a challenge applicable to the requested resource. 
    topic__links:
      self:
        href: /design/topics/http-status-401
      topicGuidelines:
        href: /design/topics/http-status-401/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-403
    topic_category: HTTP Status User Error
    topic_name: 403 Forbidden
    topic_description: 'The request was a valid request, but the server is refusing to respond to it. The user might be logged in but does not have the necessary permissions for the resource.'
    topic__links:
      self:
        href: /design/topics/http-status-403
      topicGuidelines:
        href: /design/topics/http-status-403/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-404
    topic_category: HTTP Status User Error
    topic_name: 404 Not Found
    topic_description: The requested resource could not be found but may be available in the future. Subsequent requests by the client are permissible.
    topic__links:
      self:
        href: /design/topics/http-status-404
      topicGuidelines:
        href: /design/topics/http-status-404/guidelines
    references:
      - name: HTTP Status (Get List of resources)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-1'
      - name: Delete Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
        quote: 404 Not Found HTTP status should not be utilized
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-405
    topic_category: HTTP Status User Error
    topic_name: 405 Method Not Allowed
    topic_description: |
      A request method is not supported for the requested resource; for example, a GET request on a form which requires data to be presented via POST, or a PUT request on a read-only resource.
    topic__links:
      self:
        href: /design/topics/http-status-405
      topicGuidelines:
        href: /design/topics/http-status-405/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-406
    topic_category: HTTP Status User Error
    topic_name: 406 Not Acceptable
    topic_description: The requested resource is capable of generating only content not acceptable according to the Accept headers sent in the request.
    topic__links:
      self:
        href: /design/topics/http-status-406
      topicGuidelines:
        href: /design/topics/http-status-406/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-408
    topic_category: HTTP Status User Error
    topic_name: 408 Request Timeout
    topic_description: |
      The server timed out waiting for the request. According to HTTP specifications: The client did not produce a request within the time that the server was prepared to wait. The client MAY repeat the request without modifications at any later time.
    topic__links:
      self:
        href: /design/topics/http-status-408
      topicGuidelines:
        href: /design/topics/http-status-408/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-409
    topic_category: HTTP Status User Error
    topic_name: 409 Conflict
    topic_description: |
      Indicates that the request could not be processed because of conflict in the request, such as an edit conflict between multiple simultaneous updates.
    topic__links:
      self:
        href: /design/topics/http-status-409
      topicGuidelines:
        href: /design/topics/http-status-409/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-410
    topic_category: HTTP Status User Error
    topic_name: 410 Gone
    topic_description: |
      Indicates that the resource requested is no longer available and will not be available again. This should be used when a resource has been intentionally removed and the resource should be purged. Upon receiving a 410 status code, the client should not request the resource in the future. Clients such as search engines should remove the resource from their indices. Most use cases do not require clients and search engines to purge the resource, and a *404 Not Found* may be used instead.
    topic__links:
      self:
        href: /design/topics/http-status-410
      topicGuidelines:
        href: /design/topics/http-status-410/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-411
    topic_category: HTTP Status User Error
    topic_name: 411 Length Required
    topic_description: 'The request did not specify the length of its content, which is required by the requested resource.'
    topic__links:
      self:
        href: /design/topics/http-status-411
      topicGuidelines:
        href: /design/topics/http-status-411/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-412
    topic_category: HTTP Status User Error
    topic_name: 412 Precondition Failed
    topic_description: The server does not meet one of the preconditions that the requester put on the request.
    topic__links:
      self:
        href: /design/topics/http-status-412
      topicGuidelines:
        href: /design/topics/http-status-412/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-415
    topic_category: HTTP Status User Error
    topic_name: 415 Unsupported Media Type
    topic_description: 'The request entity has a media type which the server or resource does not support. For example, the client uploads an image as image/svg+xml, but the server requires that images use a different format.'
    topic__links:
      self:
        href: /design/topics/http-status-415
      topicGuidelines:
        href: /design/topics/http-status-415/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-422
    topic_category: HTTP Status User Error
    topic_name: 422 Unprocessable Entity
    topic_description: The request was well-formed but was unable to be followed due to semantic errors.
    topic__links:
      self:
        href: /design/topics/http-status-422
      topicGuidelines:
        href: /design/topics/http-status-422/guidelines
    references:
      - name: HTTP Status (Update Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
      - name: HTTP Status (Update Partial Single Resource)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-500
    topic_category: HTTP Status Server Error
    topic_name: 500 Internal Server Error
    topic_description: 'A generic error message, given when an unexpected condition was encountered and no more specific message is suitable.'
    topic__links:
      self:
        href: /design/topics/http-status-500
      topicGuidelines:
        href: /design/topics/http-status-500/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-status-501
    topic_category: HTTP Status Server Error
    topic_name: 501 Not Implemented
    topic_description: 'The server either does not recognize the request method, or it lacks the ability to fulfill the request. Usually this implies future availability (e.g., a new feature of a web-service API).'
    topic__links:
      self:
        href: /design/topics/http-status-501
      topicGuidelines:
        href: /design/topics/http-status-501/guidelines
    references:
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
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
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/error-handling/error-handling.md'
  - topic_id: http-status
    topic_category: HTTP Protocol
    topic_name: HTTP Statuses
    topic_description: General information about HTTP statuses usage
    topic__links:
      self:
        href: /design/topics/http-status
      topicGuidelines:
        href: /design/topics/http-status/guidelines
    references:
      - name: Mapping Response Codes For Success and Failure
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#mapping-response-codes-for-success-and-failure'
      - name: HTTP Status Codes
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
  - topic_id: http-methods-delete
    topic_category: HTTP Methods
    topic_name: DELETE
    topic_description: The DELETE method deletes the specified resource.
    topic__links:
      self:
        href: /design/topics/http-methods-delete
      topicGuidelines:
        href: /design/topics/http-methods-delete/guidelines
    references:
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
  - topic_id: http-methods-get
    topic_category: HTTP Methods
    topic_name: GET
    topic_description: |
      The GET method requests a representation of the specified resource. Requests using GET should only retrieve data and should have no other effect.
    topic__links:
      self:
        href: /design/topics/http-methods-get
      topicGuidelines:
        href: /design/topics/http-methods-get/guidelines
    references:
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      - name: Get List of resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#get-list-of-resources'
      - name: Read Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#read-single-resource'
  - topic_id: http-methods-patch
    topic_category: HTTP Methods
    topic_name: PATCH
    topic_description: |
      The PATCH method applies partial modifications to a resource.
    topic__links:
      self:
        href: /design/topics/http-methods-patch
      topicGuidelines:
        href: /design/topics/http-methods-patch/guidelines
    references:
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      - name: Update Partial Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
  - topic_id: http-methods-post
    topic_category: HTTP Methods
    topic_name: POST
    topic_description: |
      The POST method requests that the server accept the entity enclosed in the request as a new subordinate of the web resource identified by the URI. The data POSTed might be, for example, an annotation for existing resources; a message for a bulletin board, newsgroup, mailing list, or comment thread; a block of data that is the result of submitting a web form to a data-handling process; or an item to add to a database.
    topic__links:
      self:
        href: /design/topics/http-methods-post
      topicGuidelines:
        href: /design/topics/http-methods-post/guidelines
    references:
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      - name: Create New Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource'
      - name: Using POST (Search)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/search/search.md#using-post'
  - topic_id: http-methods-put
    topic_category: HTTP Methods
    topic_name: PUT
    topic_description: |
      The PUT method requests that the enclosed entity be stored under the supplied URI. If the URI refers to an already existing resource, it is modified; if the URI does not point to an existing resource, then the server can create the resource with that URI.
    topic__links:
      self:
        href: /design/topics/http-methods-put
      topicGuidelines:
        href: /design/topics/http-methods-put/guidelines
    references:
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      - name: Update Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
      - name: Create New Resource - Consumer Supplied Identifier
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource---consumer-supplied-identifier'
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
      - name: HTTP Verbs
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
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
      - name: Expanding Resources Through Hypermedia Linking
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#expanding-resources-through-hypermedia-linking'
      - name: Hypermedia and REST
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/hypermedia-and-rest/hypermedia-and-rest.md'
      - name: Relationships and Sub-Resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
      - name: Hypermedia Links (Pagination)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#hypermedia-links'
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
      - name: Expanding Resources Through Hypermedia Linking
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#expanding-resources-through-hypermedia-linking'
      - name: Support Hypermedia
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/rest-principles/rest-principles.md#support-hypermedia'
      - name: Hypermedia and REST
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/hypermedia-and-rest/hypermedia-and-rest.md'
      - name: Relationships and Sub-Resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
      - name: Hypermedia Links (Pagination)
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#hypermedia-links'
      - name: Hypermedia Response Format
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/response-format/response-format.md'
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
      - name: Building Your Resource Taxonomy
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#building-your-resource-taxonomy'
      - name: Resource naming
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#resource-naming'
  - topic_id: resource-creation-with-id
    topic_category: Resources
    topic_name: Create resource with a specific ID
    topic_description: How to create resource with a provided id
    topic__links:
      self:
        href: /design/topics/resource-creation-with-id
      topicGuidelines:
        href: /design/topics/resource-creation-with-id/guidelines
    references:
      - name: Create New Resource - Consumer Supplied Identifier
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource---consumer-supplied-identifier'
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
      - name: Create New Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource'
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
      - name: Delete Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
  - topic_id: resource-id
    topic_category: Resources
    topic_name: Resource ID
    topic_description: What is a resource ID and/or how it's built
    topic__links:
      self:
        href: /design/topics/resource-id
      topicGuidelines:
        href: /design/topics/resource-id/guidelines
    references:
      - name: Composite Keys
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/faq/faq.md#composite-keys'
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
      - name: How to Handle Resource Relationships and Composition
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#how-to-handle-resource-relationships-and-composition'
      - name: Relationships and Sub-Resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
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
      - name: Update Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
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
      - name: Field selection
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#field-selection'
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
      - name: Read Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#read-single-resource'
  - topic_id: resource-state
    topic_category: Resources
    topic_name: Resource's state
    topic_description: How to change a resource's state/status (like processed/sent/paid/...)
    topic__links:
      self:
        href: /design/topics/resource-state
      topicGuidelines:
        href: /design/topics/resource-state/guidelines
    references:
      name: Resource's state
      description: How to change a resource's state/status (like processed/sent/paid/...)
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
      - name: Update Partial Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
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
      - name: Update Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
      - name: Update Partial Single Resource
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
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
      - name: URI Components
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/uri-components/uri-components.md'
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
      - name: Building Your Resource Taxonomy
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#building-your-resource-taxonomy'
      - name: Defining Resource Lifecycles
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#defining-resource-lifecycles'
      - name: Resources
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/resources/resources.md'
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
      - name: API clients MUST use an API Key
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md#api-clients-must-use-an-api-key'
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
      - name: Security and Authentication
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/security-and-authentication/security-and-authentication.md'
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
      - name: Version
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/uri-components/uri-components.md#version'
---