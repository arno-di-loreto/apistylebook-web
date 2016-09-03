---
layout: topic
title: URL format
permalink: /design/topics/resource-url-format
sort: Resources_URL format
topic_id: resource-url-format
topic_category: Resources
topic_name: URL format
topic_description: How to design URLs
guidelines:
  - guideline_id: atlassian-rest-api-design-guidelines-version-1
    guideline_title: Atlassian REST API Design Guidelines version 1
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1/topics
    references:
      - name: REST Resources
        url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
        quote: URI Structure
  - guideline_id: atlassian-rest-api-policy
    guideline_title: Atlassian REST API Policy
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-09-01T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/atlassian-rest-api-policy
      guidelineTopics:
        href: /design/guidelines/atlassian-rest-api-policy/topics
    references:
      - name: Stable URIs
        url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-StableURIs'
  - guideline_id: ausdto-api-design-guide
    guideline_title: API Design Guide
    guideline_type: website
    guideline_url: 'https://apiguide.readthedocs.io/en/latest/index.html'
    guideline_company: Australian Digital Transformation Office
    guideline_companyLogoUrl: /media/logos/ausdto.png
    guideline_companyUrl: 'https://www.dto.gov.au/'
    guideline_date: 2015-10-20T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/ausdto-api-design-guide
      guidelineTopics:
        href: /design/guidelines/ausdto-api-design-guide/topics
    references:
      - name: URL Depth
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#url-depth'
      - name: Good RESTful URL examples
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#good-restful-url-examples'
  - guideline_id: cisco-api-design-guide
    guideline_title: API Design Guide
    guideline_type: github
    guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
    guideline_company: Cisco
    guideline_companyLogoUrl: /media/logos/cisco.png
    guideline_companyUrl: 'http://developer.cisco.com/'
    guideline_date: 2015-08-21T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline_attachedDocuments:
      - name: REST API Design Principles
        description: A summary of common REST API design constraints and conventions
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md'
        type: github
        referenced:
          - name: Preface
            url: 'https://github.com/CiscoDevNet/api-design-guide#1-preface'
      - name: Tracking ID flow
        description: A sequence diagram explaning
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/trackingid-flow.png'
        type: github
        referenced:
          - name: TrackingID Header
            description: A sequence diagram explaning the use of the tracking ID
            url: 'https://github.com/CiscoDevNet/api-design-guide#352-trackingid-header'
    guideline_remarks:
      - 'broken links due to typo error in https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
    guideline__links:
      self:
        href: /design/guidelines/cisco-api-design-guide
      guidelineTopics:
        href: /design/guidelines/cisco-api-design-guide/topics
    references:
      - name: 3.4 URL Format
        url: 'https://github.com/CiscoDevNet/api-design-guide#34-url-format'
      - name: URL Paths
        document: REST API Design Principles
        url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#url-paths'
  - guideline_id: cloud-foundy-cloud-controller-api-style-guide
    guideline_title: Cloud Controller API v3 Style Guide (Proposal)
    guideline_type: github
    guideline_url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
    guideline_company: Cloud Foundry
    guideline_companyLogoUrl: /media/logos/cloudfoundry.png
    guideline_companyUrl: 'https://www.cloudfoundry.org/'
    guideline_date: 2016-05-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
      guidelineTopics:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
    references:
      - name: URL Structure
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
  - guideline_id: haufe-api-styleguide
    guideline_title: Haufe API style guide
    guideline_type: github
    guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
    guideline_company: Haufe
    guideline_companyLogoUrl: /media/logos/haufe.png
    guideline_companyUrl: 'http://dev.haufe.com/'
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/haufe-api-styleguide
      guidelineTopics:
        href: /design/guidelines/haufe-api-styleguide/topics
    references:
      - name: URI Components
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/uri-components/uri-components.md'
  - guideline_id: heroku-http-api-design-guide
    guideline_title: HTTP API Design Guide
    guideline_type: gitbook
    guideline_url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
    guideline_company: Heroku
    guideline_companyLogoUrl: /media/logos/heroku.png
    guideline_companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
    guideline_date: 2016-07-05T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/heroku-http-api-design-guide
      guidelineTopics:
        href: /design/guidelines/heroku-http-api-design-guide/topics
    references:
      - name: Use consistent path formats
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/use-consistent-path-formats.html'
      - name: Downcase paths and attributes
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/downcase-paths-and-attributes.html'
      - name: Minimize path nesting
        url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/minimize-path-nesting.html'
  - guideline_id: microsoft-rest-api-guidelines
    guideline_title: Microsoft REST API Guidelines
    guideline_type: github
    guideline_url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md'
    guideline_company: Microsoft
    guideline_companyLogoUrl: /media/logos/microsoft.png
    guideline_companyUrl: 'https://opensource.microsoft.com/'
    guideline_date: 2016-07-19T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/microsoft-rest-api-guidelines
      guidelineTopics:
        href: /design/guidelines/microsoft-rest-api-guidelines/topics
    references:
      - name: URL Structure
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#71-url-structure'
      - name: URL Length
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#72-url-length'
      - name: Collection URL patterns
        url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#93-collection-url-patterns'
  - guideline_id: paypal-api-style-guide
    guideline_title: API Style Guide
    guideline_type: github
    guideline_url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
    guideline_company: PayPal
    guideline_companyLogoUrl: /media/logos/paypal.png
    guideline_companyUrl: 'https://developer.paypal.com/'
    guideline_date: 2016-08-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/paypal-api-style-guide
      guidelineTopics:
        href: /design/guidelines/paypal-api-style-guide/topics
    references:
      - name: URL Components
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#uri-components'
      - name: Update Partial Single Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
  - guideline_id: redhat-thoughts-on-restful-api-design
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
    guideline__links:
      self:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design
      guidelineTopics:
        href: /design/guidelines/redhat-thoughts-on-restful-api-design/topics
    references:
      - name: URLs
        url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
  - guideline_id: white-house-web-api-standards
    guideline_title: White House Web API Standards
    guideline_type: github
    guideline_url: 'https://github.com/WhiteHouse/api-standards'
    guideline_company: White House
    guideline_companyLogoUrl: /media/logos/whitehouse.png
    guideline_companyUrl: 'https://www.whitehouse.gov/developers'
    guideline_date: 2015-02-24T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/white-house-web-api-standards
      guidelineTopics:
        href: /design/guidelines/white-house-web-api-standards/topics
    references:
      - name: RESTful URLs
        url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#restful-urls'
  - guideline_id: zalando-restful-api-guidelines
    guideline_title: RESTFul API Guidelines
    guideline_type: website
    guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
    guideline_company: Zalando
    guideline_companyLogoUrl: /media/logos/zalando.png
    guideline_companyUrl: 'https://tech.zalando.de/'
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-08-28T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/zalando-restful-api-guidelines
      guidelineTopics:
        href: /design/guidelines/zalando-restful-api-guidelines/topics
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
---