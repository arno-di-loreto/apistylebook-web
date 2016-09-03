---
layout: guideline
title: API Style Guide
permalink: /design/guidelines/paypal-api-style-guide
sort: PayPal_API Style Guide
guideline_id: paypal-api-style-guide
guideline_title: API Style Guide
guideline_type: github
guideline_url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
guideline_company: PayPal
guideline_companyLogoUrl: /media/logos/paypal.png
guideline_companyUrl: 'https://developer.paypal.com/'
guideline_date: 2016-08-11T00:00:00.000Z
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
      - name: Time Selection
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#time-selection'
      - name: Complex Operation - Search
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---search'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#paging'
      - name: Paging (Complex Operation - Search)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#paging-1'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sorting'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: Sub-Resource Collection
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sub-resource-collection'
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
      - name: Read-only resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-only-resources'
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
      - name: HTTP Status (Collections)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
      - name: Update Partial Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
      - name: Delete Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
      - name: HTTP Status (Collections)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
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
      - name: HTTP Status (Collections)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
      - name: Delete Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
  - topic_id: http-status-422
    topic_category: HTTP Status
    topic_name: HTTP Status 422
    topic_description: When to use HTTP status 422
    topic__links:
      self:
        href: /design/topics/http-status-422
      topicGuidelines:
        href: /design/topics/http-status-422/guidelines
    references:
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
      - name: HTTP Status (Collections)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: Delete Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: HTTP Status (Read Single Resource)
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: Update Partial Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: Create New Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
      - name: Update Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
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
      - name: Paging Hypermedia Links
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#hypermedia-links'
      - name: Create New Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
        quote: Hypermedia links provide an easy way to get the URL of the newly created resource
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
      - name: Paging Hypermedia Links
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#hypermedia-links'
      - name: Create New Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
        quote: Hypermedia links provide an easy way to get the URL of the newly created resource
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
      - name: Collection Resources
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        quote: Collection resource names should be plural nouns
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
      - name: Filtering
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#filtering'
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
      name: Performance and bandwidth
      description: How to deal with high traffic or consumers with low bandwith
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
      - name: Complex Operation
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource---consumer-supplied-identifier'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
      - name: Complex Operation - Composite
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---composite'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-single-resource'
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
      - name: Complex Operation - Transient
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---transient'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
      - name: URL Components
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#uri-components'
      - name: Update Partial Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
      - name: Read Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-single-resource'
      - name: Sub-Resource Singleton
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sub-resource-singleton'
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
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#version'
---