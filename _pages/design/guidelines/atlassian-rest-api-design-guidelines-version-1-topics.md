---
layout: guideline
title: Atlassian REST API Design Guidelines version 1
permalink: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
sort: Atlassian_Atlassian REST API Design Guidelines version 1
guideline_id: atlassian-rest-api-design-guidelines-version-1
guideline_title: Atlassian REST API Design Guidelines version 1
guideline_type: website
guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
guideline_company: Atlassian
guideline_companyLogoUrl: /media/logos/atlassian.png
guideline_companyUrl: 'https://developer.atlassian.com/'
guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-design-guidelines-version-1.png
guideline_date: 2016-01-22T00:00:00.000Z
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: 'Standard Query Parameters in URIs (start-index, max-results)'
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: URI Structure
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Collections of Entities
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Representations (Content Types) of Entities
      - name: 'Appendix B: Basic Data Types'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixB:BasicDataTypes'
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
      - name: Using these Guidelines
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-UsingtheseGuidelines'
        quote: We strongly recommend that someone who is familiar with these guidelines should review your REST API code
      - name: Version Control for APIs
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-VersionControlforAPIs'
        quote: When to Change the Version
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Version Control for Entities
      - name: Caching
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Caching'
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Entities SHOULD be served with an ETag header.
      - name: Caching
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Caching'
        quote: 'ETag, If-None-Match'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: Concurrency
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Concurrency'
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: 'Appendix A: Response Codes'
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-AppendixA:ResponseCodes'
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
      - name: Concurrency
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Concurrency'
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
      - name: Concurrency
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Concurrency'
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Hypertext Linking within an Entity
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Hypertext Linking within an Entity
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Hypertext Linking within an Entity
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
      - name: Concurrency
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Concurrency'
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Standard Query Parameters in URIs (expand)
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: Title Expansion for Entities
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
      - name: Concurrency
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Concurrency'
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: URI Structure
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
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
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
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Security'
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
      - name: Version Control for APIs
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-VersionControlforAPIs'
---