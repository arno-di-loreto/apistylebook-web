---
layout: guideline
title: Thoughts on RESTful API Design
permalink: /design/guidelines/redhat-thoughts-on-restful-api-design
sort: Red Hat_Thoughts on RESTful API Design
guideline_id: redhat-thoughts-on-restful-api-design
guideline_title: Thoughts on RESTful API Design
guideline_type: website
guideline_url: 'http://restful-api-design.readthedocs.io/en/latest/'
guideline_company: Red Hat
guideline_companyLogoUrl: /media/logos/redhat.png
guideline_companyUrl: 'https://www.redhat.com/'
guideline_authors:
  - name: Geert Jansen
    twitter: 1geertj
guideline_date: 2012-11-15T00:00:00.000Z
guideline_reviewDate: 2016-08-18T00:00:00.000Z
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
      - name: Asynchronous Requests
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#asynchronous-requests'
  - topic_id: collection-filtering
    topic_category: Collection Resources
    topic_name: Filtering
    topic_description: How to select some resources in a collection
    topic__links:
      self:
        href: /design/topics/collection-filtering
      topicGuidelines:
        href: /design/topics/collection-filtering/guidelines
    references: null
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
      - name: Ranges Pagination
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#ranges-pagination'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: URLs
        url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
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
      - name: Resource Data
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#resource-data'
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
      - name: Forms
        quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
        url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
  - topic_id: guiding-input
    topic_category: Miscellaneous
    topic_name: Guiding inputs
    topic_description: How to help consumers or end user to input relevant data
    topic__links:
      self:
        href: /design/topics/guiding-input
      topicGuidelines:
        href: /design/topics/guiding-input/guidelines
    references:
      - name: Forms
        quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
        url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
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
      - name: Representations
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#representations'
      - name: Content-Types
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#content-types'
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
      - name: Link Headers
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: REST Metadata
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
      - name: Link Headers
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
      - name: Relationships
        url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
      - name: Forms
        quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
        url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
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
      - name: REST Metadata
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
      - name: Link Headers
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
      - name: Relationships
        url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
      - name: Notifications
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#notifications'
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
      - name: Actions
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#actions'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: REST Metadata
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
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
      - name: PATCH vs PUT
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#patch-vs-put'
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
      - name: Relationships
        url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: Methods
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
      - name: URLs
        url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
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
      - name: Resources
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html'
      - name: URLs
        url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
---