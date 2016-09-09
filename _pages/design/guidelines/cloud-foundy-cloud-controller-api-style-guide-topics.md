---
layout: guideline
title: Cloud Controller API v3 Style Guide (Proposal)
permalink: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
sort: Cloud Foundry_Cloud Controller API v3 Style Guide (Proposal)
guideline_id: cloud-foundy-cloud-controller-api-style-guide
guideline_title: Cloud Controller API v3 Style Guide (Proposal)
guideline_type: github
guideline_url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
guideline_company: Cloud Foundry
guideline_companyLogoUrl: /media/logos/cloudfoundry.png
guideline_companyUrl: 'https://www.cloudfoundry.org/'
guideline_screenshotUrl: /media/screenshots/cloud-foundy-cloud-controller-api-style-guide.png
guideline_date: 2016-05-11T00:00:00.000Z
guideline_reviewDate: 2016-08-18T00:00:00.000Z
topics:
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
      - name: Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
      - name: Links
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
      - name: Includind Related Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
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
      - name: Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
      - name: Links
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
      - name: Links
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
      - name: Requests
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#requests'
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
      - name: GET
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
      - name: POST
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#post'
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
      - name: PUT
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#put'
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
      - name: DELETE
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#delete'
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
      - name: PATCH
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
      - name: Responses Codes
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#response-codes'
      - name: GET responses (Resource)
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-resource'
      - name: GET responses (Collection)
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-collection'
      - name: POST responses
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses'
      - name: PUT responses
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-1'
      - name: PATCH responses
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-2'
      - name: DELETE responses
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-3'
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
      - name: Successful Requests
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
      - name: Successful Requests
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
      - name: Successful Requests
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
      - name: Successful Requests
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
  - topic_id: http-status-302
    topic_category: HTTP Status Redirection
    topic_name: 302 Found
    topic_description: |
      Common way of performing URL redirection. An HTTP response with this status code will additionally provide a URL in the location header field. The user agent (e.g. a web browser) is invited by a response with this code to make a second, otherwise identical, request to the new URL specified in the location field. 
    topic__links:
      self:
        href: /design/topics/http-status-302
      topicGuidelines:
        href: /design/topics/http-status-302/guidelines
    references:
      - name: Redirections
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#redirection'
  - topic_id: http-status-303
    topic_category: HTTP Status Redirection
    topic_name: 303 See Other
    topic_description: |
      The response to the request can be found under another URI using a GET method. When received in response to a POST (or PUT/DELETE), the client should presume that the server has received the data and should issue a redirect with a separate GET message.
    topic__links:
      self:
        href: /design/topics/http-status-303
      topicGuidelines:
        href: /design/topics/http-status-303/guidelines
    references:
      - name: Redirections
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#redirection'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: Client Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
      - name: Server Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#server-errors'
  - topic_id: http-status-503
    topic_category: HTTP Status Server Error
    topic_name: 503 Service Unavailable
    topic_description: 'The server is currently unavailable (because it is overloaded or down for maintenance). Generally, this is a temporary state.'
    topic__links:
      self:
        href: /design/topics/http-status-503
      topicGuidelines:
        href: /design/topics/http-status-503/guidelines
    references:
      - name: Server Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#server-errors'
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
      - name: Errors
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#errors'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
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
      - name: Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
      - name: Requesting Partiel Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#requesting-partial-resources'
      - name: Nested Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#nested-resources'
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
      - name: Includind Related Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#post'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#delete'
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
      - name: PUT
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#put'
      - name: Actions
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#actions'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#relationships'
      - name: Links
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#collections'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
      - name: Pagination
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#pagination'
      - name: Pagination of Related Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#pagination-of-related-resources'
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
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#filtering'
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
      - name: Query Parameters
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
      - name: Field Names
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#field-names'
      - name: URL Structure
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
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
      - name: Query Parameters
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
      - name: Field Names
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#field-names'
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
      - name: Query Parameters
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
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
      - name: Asynchronicity
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#asynchronicity'
---