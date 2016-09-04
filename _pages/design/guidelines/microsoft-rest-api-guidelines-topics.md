---
layout: guideline
title: Microsoft REST API Guidelines
permalink: /design/guidelines/microsoft-rest-api-guidelines
sort: Microsoft_Microsoft REST API Guidelines
guideline_id: microsoft-rest-api-guidelines
guideline_title: Microsoft REST API Guidelines
guideline_type: github
guideline_url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md'
guideline_company: Microsoft
guideline_companyLogoUrl: /media/logos/microsoft.png
guideline_companyUrl: 'https://opensource.microsoft.com/'
guideline_screenshotUrl: /media/screenshots/microsoft-rest-api-guidelines.png
guideline_date: 2016-07-19T00:00:00.000Z
guideline_reviewDate: 2016-08-31T00:00:00.000Z
topics:
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
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#97-filtering'
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
      - name: Big collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#94-big-collections'
      - name: Pagination
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#98-pagination'
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
      - name: Variable order rule
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#62-variable-order-rule'
      - name: Sorting collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#96-sorting-collections'
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
      - name: Collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#9-collections'
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
      - name: CORS
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#8-cors'
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
      - name: Guidelines for dates and times
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#112-guidelines-for-dates-and-times'
      - name: JSON serialization of dates and times
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#113-json-serialization-of-dates-and-times'
      - name: Durations
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#114-durations'
      - name: Intervals
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#115-intervals'
      - name: Repeating intervals
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#116-repeating-intervals'
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
      - name: Response Formats
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#710-response-formats'
      - name: JSON standardizations
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#11-json-standardizations'
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
      - name: Client Guidance
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#6-client-guidance'
      - name: Client library optional
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#712-client-library-optional'
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
      - name: Options and link headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
        quote: 'In addition, services SHOULD include a Link header (see RFC 5988) to point to documentation for the resource'
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
      - name: Errors
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#51-errors'
      - name: Faults
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#52-faults'
      - name: Long running API faults
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#55-long-running-api-faults'
      - name: Silent Fail Rule
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#63-silent-fail-rule'
      - name: Unsupported requests
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#15-unsupported-requests'
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
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#3-introduction'
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
      - name: Interpreting The Guidelines
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#4-interpreting-the-guidelines'
      - name: When to version
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#122-when-to-version'
      - name: Definition of a breaking change
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#123-definition-of-a-breaking-change'
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
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
        quote: 'If-Match, If-None-Match, If-Range'
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
        quote: ETag
      - name: Retention policy for operation results
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#133-retention-policy-for-operation-results'
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
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
        quote: Accept Content Type
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
        quote: Content Type
      - name: Clients-specified response format
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#7101-clients-specified-response-format'
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
      - name: POST
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
        quote: POST operations SHOULD support the Location response header
      - name: Options and link headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
      - name: Custom Headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#77-custom-headers'
      - name: Specifying headers as query parameters
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#78-specifying-headers-as-query-parameters'
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
      - name: Error condition responses
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#7102-error-condition-responses'
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
      - name: Errors
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#51-errors'
      - name: Faults
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#52-faults'
      - name: HTTP Status Codes
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#711-http-status-codes'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
      - name: Options and link headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
      - name: PATCH
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
      - name: Creating resources via PATCH (UPSERT semantics)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
      - name: POST
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
      - name: Changing collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
      - name: POST (Long running operations)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1322-post'
      - name: 'POST, hybrid model (Long running operations)'
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1323-post-hybrid-model'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
      - name: Changing collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
      - name: PUT (Long running operations)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1321-put'
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
      - name: Supported Methods
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
      name: HTTP protocol
      description: General informations about HTTP protocol
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
      - name: Options and link headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
      - name: Big collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#94-big-collections'
        quote: the serialization payload MUST contain the opaque URL for the next page
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
      - name: 'The typical flow, push notifications'
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1328-the-typical-flow-push-notifications'
      - name: Push notifications via webhooks
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#14-push-notifications-via-webhooks'
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
  - topic_id: resource-change-tracking
    topic_category: Resources
    topic_name: Track change
    topic_description: How to track change on resources
    topic__links:
      self:
        href: /design/topics/resource-change-tracking
      topicGuidelines:
        href: /design/topics/resource-change-tracking/guidelines
    references:
      - name: Delta queries
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#10-delta-queries'
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
      - name: Creating resources via PATCH (UPSERT semantics)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
      - name: Changing collections
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
  - topic_id: resource-id-semantic
    topic_category: Resources
    topic_name: ID with semantic
    topic_description: Using meaningful ids (like `me`)
    topic__links:
      self:
        href: /design/topics/resource-id-semantic
      topicGuidelines:
        href: /design/topics/resource-id-semantic/guidelines
    references:
      - name: Canonical identifier
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#73-canonical-identifier'
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
      - name: Canonical identifier
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#73-canonical-identifier'
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
      name: Batch Bulk
      description: How to handle batch/bulk processing/creation/update/... (e.g. handle multiple resources at conce)
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
      - name: Standard request headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
        quote: 'Prefer return=minimal, return=representation'
      - name: Standard response headers
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
        quote: Preference-Applied
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
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
      - name: Creating resources via PATCH (UPSERT semantics)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
      - name: PATCH
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
      - name: Creating resources via PATCH (UPSERT semantics)
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
      - name: URL Structure
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#71-url-structure'
      - name: URL Length
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#72-url-length'
      - name: Collection URL patterns
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#93-collection-url-patterns'
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
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#148-security'
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
      - name: PII parameters
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#79-pii-parameters'
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
      - name: Guidelines for existing services and versioning of services
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#42-guidelines-for-existing-services-and-versioning-of-services'
      - name: Versioning
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#12-versioning'
---