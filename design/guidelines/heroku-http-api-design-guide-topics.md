---
layout: guideline
title: HTTP API Design Guide
permalink: /design/guidelines/heroku-http-api-design-guide
sort: Heroku_HTTP API Design Guide
guideline_id: heroku-http-api-design-guide
guideline_title: HTTP API Design Guide
guideline_type: gitbook
guideline_url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
guideline_company: Heroku
guideline_companyLogoUrl: /media/logos/heroku.png
guideline_companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
guideline_screenshotUrl: /media/screenshots/heroku-http-api-design-guide.png
guideline_date: 2016-07-05T00:00:00.000Z
guideline_reviewDate: 2016-08-31T00:00:00.000Z
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
      - name: Divide Large Responses Across Requests with Ranges
        description: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/divide-large-responses-across-requests-with-ranges.html'
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
      - name: Provide standard timestamps
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
      - name: Use UTC times formatted in ISO8601
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/use-utc-times-formatted-in-iso8601.html'
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
      - name: Accept serialized JSON in request bodies
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/accept-serialized-json-in-request-bodies.html'
      - name: Provide standard timestamps
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
      - name: Nest foreign key relations
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/nest-foreign-key-relations.html'
      - name: Keep JSON minified in all responses
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/keep-json-minified-in-all-responses.html'
  - topic_id: debug-diagnose
    topic_category: Miscellaneous
    topic_name: Debug and diagnose
    topic_description: How to provide informations to debug and diagnose
    topic__links:
      self:
        href: /design/topics/debug-diagnose
      topicGuidelines:
        href: /design/topics/debug-diagnose/guidelines
    references:
      - name: Provide Request-Ids for Introspection
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/provide-request-ids-for-introspection.html'
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
      - name: Provide machine-readable JSON schema
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-machine-readable-json-schema.html'
      - name: Provide human-readable docs
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-human-readable-docs.html'
      - name: Provide executable examples
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-executable-examples.html'
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
      - name: Separate Concerns
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/separate-concerns.html'
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
      - name: Support ETags for Caching
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/support-etags-for-caching.html'
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
      - name: Require Versioning in the Accepts Header
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-versioning-in-the-accepts-header.html'
      - name: Support ETags for Caching
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/support-etags-for-caching.html'
      - name: Provide Request-Ids for Introspection
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/provide-request-ids-for-introspection.html'
      - name: Divide Large Responses Across Requests with Ranges
        description: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/divide-large-responses-across-requests-with-ranges.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
  - topic_id: http-status-202
    topic_category: HTTP Status Success
    topic_name: 202 Accepted
    topic_description: |
      The request has been accepted for processing, but the processing has not been completed. The request might or might not be eventually acted upon, and may be disallowed when processing occurs.
    topic__links:
      self:
        href: /design/topics/http-status-202
      topicGuidelines:
        href: /design/topics/http-status-202/guidelines
    references:
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
  - topic_id: http-status-206
    topic_category: HTTP Status Success
    topic_name: 206 Partial Content
    topic_description: |
      The server is delivering only part of the resource (byte serving) due to a range header sent by the client. The range header is used by HTTP clients to enable resuming of interrupted downloads, or split a download into multiple simultaneous streams.
    topic__links:
      self:
        href: /design/topics/http-status-206
      topicGuidelines:
        href: /design/topics/http-status-206/guidelines
    references:
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Require Secure Connections
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-secure-connections.html'
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
  - topic_id: http-status-429
    topic_category: HTTP Status User Error
    topic_name: 429 Too Many Requests
    topic_description: The user has sent too many requests in a given amount of time. Intended for use with rate-limiting schemes.
    topic__links:
      self:
        href: /design/topics/http-status-429
      topicGuidelines:
        href: /design/topics/http-status-429/guidelines
    references:
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Generate structured errors
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/generate-structured-errors.html'
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
      - name: Return appropriate status codes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
      - name: Downcase paths and attributes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/downcase-paths-and-attributes.html'
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
      - name: Resource names
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/resource-names.html'
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
      - name: Keep JSON minified in all responses
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/keep-json-minified-in-all-responses.html'
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
      - name: Show rate limit status
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/show-rate-limit-status.html'
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
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/actions.html'
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
      - name: Provide full resources where available
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
      - name: Provide full resources where available
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
      - name: Support non-id dereferencing for convenience
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/support-non-id-dereferencing-for-convenience.html'
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
      - name: Support non-id dereferencing for convenience
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/support-non-id-dereferencing-for-convenience.html'
      - name: Provide resource (UU)IDs
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-resource-uuids.html'
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
      - name: Nest foreign key relations
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/nest-foreign-key-relations.html'
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
      - name: Provide full resources where available
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
      - name: Provide full resources where available
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
      - name: Use consistent path formats
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/use-consistent-path-formats.html'
      - name: Downcase paths and attributes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/downcase-paths-and-attributes.html'
      - name: Minimize path nesting
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/minimize-path-nesting.html'
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
      - name: Require Secure Connections
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-secure-connections.html'
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
      - name: Require Versioning in the Accepts Header
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-versioning-in-the-accepts-header.html'
      - name: Describe stability
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/describe-stability.html'
---