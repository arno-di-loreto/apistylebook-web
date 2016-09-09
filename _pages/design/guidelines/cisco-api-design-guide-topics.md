---
layout: guideline
title: API Design Guide
permalink: /design/guidelines/cisco-api-design-guide
sort: Cisco_API Design Guide
guideline_id: cisco-api-design-guide
guideline_title: API Design Guide
guideline_type: github
guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
guideline_company: Cisco
guideline_companyLogoUrl: /media/logos/cisco.png
guideline_companyUrl: 'http://developer.cisco.com/'
guideline_screenshotUrl: /media/screenshots/cisco-api-design-guide.png
guideline_date: 2015-08-21T00:00:00.000Z
guideline_reviewDate: 2016-08-18T00:00:00.000Z
topics:
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
      - name: 3.1 Security
        url: 'https://github.com/CiscoDevNet/api-design-guide#31-security'
      - name: 3.2 Authentication and Representation
        quote: 'The REST API MUST use OAuth2 implementation for user authentication and authorization, exclusively'
        url: 'https://github.com/CiscoDevNet/api-design-guide#32-authentication-and-authorization'
      - name: 3.6.8 Safe and Non-Safe Methods
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: 3.3 Representations
        quote: 3.3.3 A resource identifier labeled "url" MUST be present in all RESTful API resource representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
      - name: 3.3 Representations
        quote: 3.3.3 A resource identifier labeled "url" MUST be present in all RESTful API resource representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
  - topic_id: api-chaining
    topic_category: Miscellaneous
    topic_name: API chaining
    topic_description: How to chain API call in internal systems
    topic__links:
      self:
        href: /design/topics/api-chaining
      topicGuidelines:
        href: /design/topics/api-chaining/guidelines
    references:
      - name: 3.5.2 TrackingID Header
        url: 'https://github.com/CiscoDevNet/api-design-guide#352-trackingid-header'
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
      - name: 3.5.1 Standard Headers
        quote: 'ETag, If-Match, If-None-Match'
        url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
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
      - name: 3.3 Representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
      - name: 3.5.1 Standard Headers
        quote: 'Accept header, Content-Type header'
        url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
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
      - name: 3.5 HTTP Headers
        url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
      - name: 3.6.1 POST
        quote: Location header
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
      - name: 3.6 HTTP Verbs
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
      - name: REST Methods
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#rest-methods'
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
      - name: 3.6.3 GET
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.1 POST
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
      - name: 3.6.2 PUT
        url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
      - name: 3.6.4 DELETE
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: 3.6.5 PATCH
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
  - topic_id: http-methods-head
    topic_category: HTTP Methods
    topic_name: HEAD
    topic_description: |
      The HEAD method asks for a response identical to that of a GET request, but without the response body. This is useful for retrieving meta-information written in response headers, without having to transport the entire content.
    topic__links:
      self:
        href: /design/topics/http-methods-head
      topicGuidelines:
        href: /design/topics/http-methods-head/guidelines
    references:
      - name: 3.6.6 HEAD
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
  - topic_id: http-methods-options
    topic_category: HTTP Methods
    topic_name: OPTIONS
    topic_description: |
      The OPTIONS method returns the HTTP methods that the server supports for the specified URL. This can be used to check the functionality of a web server by requesting '*' instead of a specific resource.
    topic__links:
      self:
        href: /design/topics/http-methods-options
      topicGuidelines:
        href: /design/topics/http-methods-options/guidelines
    references:
      - name: 3.6.7 OPTIONS
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
  - topic_id: http-methods-alternative
    topic_category: HTTP Methods
    topic_name: Forbidden methods alternatives
    topic_description: What to do when only possible HTTP methods are POST and GET
    topic__links:
      self:
        href: /design/topics/http-methods-alternative
      topicGuidelines:
        href: /design/topics/http-methods-alternative/guidelines
    references:
      - name: 3.7 Alternative Forms
        url: 'https://github.com/CiscoDevNet/api-design-guide#37-alternative-forms'
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
      - name: 3.9 Status Codes
        url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
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
      - name: 3.9 Status Codes
        url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
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
      - name: 3.9 Status Codes
        quote: 3.9.4 Documentation of response payloads MUST NOT reveal internal implementation details of the server.
        url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
      - name: API Documentation
        document: null
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#api-documentation'
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
      - name: 3 Guidelines
        quote: 'Reference Representation, Narrow Representation, Wide Representation'
        url: 'https://github.com/CiscoDevNet/api-design-guide#3-guidelines'
      - name: 3.3 Representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
      - name: 3.4 URL Format
        url: 'https://github.com/CiscoDevNet/api-design-guide#34-url-format'
      - name: URL Paths
        document: REST API Design Principles
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#url-paths'
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
      - name: 3.4.2 User Scoped Endpoints
        url: 'https://github.com/CiscoDevNet/api-design-guide#342-user-scoped-endpoints'
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
      - name: 3.6.3 GET
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.3.6 Services MAY support partial retrieval of resource state
        quote: RFC-3986
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.3 GET
        quote: 'If a service supports the fields parameter, then a value of @reference, @narrow, or @wide SHOULD...'
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.1 POST
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
      - name: 3.6.2 PUT
        url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
      - name: 3.6.2 PUT
        url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
      - name: 3.6.2 PUT
        url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
      - name: 3.6.5 PATCH
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: 3.6.5 PATCH
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: 3.6.4 DELETE
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
      - name: '3.11 Bulk, Batch, and Multi-Result Operations'
        url: 'https://github.com/CiscoDevNet/api-design-guide#311-bulk-batch-and-multi-result-operations'
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
      - name: 3.8 Action Resources
        url: 'https://github.com/CiscoDevNet/api-design-guide#38-action-resources'
      - name: 3.6.1 POST
        url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
      - name: 3.6.3 GET
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.3 GET
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.6.3 GET
        url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
      - name: 3.3 Representations
        quote: '3.3.11 With regard to JSON representation property names, and URL query parameters, services SHOULD...'
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
      - name: 3.3 Representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
      - name: URL Paths
        document: REST API Design Principles
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#url-paths'
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
      - name: 3.3 Representations
        quote: ... prefer the native JSON boolean type ...
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
      - name: 3.3 Representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
        quote: 3.3.8 Date and time fields MUST be represented as strings and formatted according to RFC-3339
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
      - name: JSON Attributes
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#json-attributes'
  - topic_id: undo
    topic_category: Miscellaneous
    topic_name: Undo
    topic_description: How to undo things
    topic__links:
      self:
        href: /design/topics/undo
      topicGuidelines:
        href: /design/topics/undo/guidelines
    references:
      - name: 3.6 HTTP Verbs
        url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
        quote: '*3.6.4.3 *The POST verb MAY be used to reverse the soft-delete of a resource, using an undelete parameter'
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
      - name: 3.13 Versioning
        url: 'https://github.com/CiscoDevNet/api-design-guide#313-versioning'
---