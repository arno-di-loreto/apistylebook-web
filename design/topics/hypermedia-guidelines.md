---
layout: topic
title: Hypermedia
permalink: /design/topics/hypermedia
sort: Hypermedia_Hypermedia
topic_id: hypermedia
topic_category: Hypermedia
topic_name: Hypermedia
topic_description: How to use hypermedia
guidelines:
  - guideline_id: atlassian-rest-api-design-guidelines-version-1
    guideline_title: Atlassian REST API Design Guidelines version 1
    guideline_type: website
    guideline_url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
    guideline_company: Atlassian
    guideline_companyLogoUrl: /media/logos/atlassian.png
    guideline_companyUrl: 'https://developer.atlassian.com/'
    guideline_screenshotUrl: /media/screenshots/atlassian-rest-api-design-guidelines-version-1.png
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
        quote: Hypertext Linking within an Entity
  - guideline_id: ausdto-api-design-guide
    guideline_title: API Design Guide
    guideline_type: website
    guideline_url: 'https://apiguide.readthedocs.io/en/latest/index.html'
    guideline_company: Australian Digital Transformation Office
    guideline_companyLogoUrl: /media/logos/ausdto.png
    guideline_companyUrl: 'https://www.dto.gov.au/'
    guideline_screenshotUrl: /media/screenshots/ausdto-api-design-guide.png
    guideline_date: 2015-10-20T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/ausdto-api-design-guide
      guidelineTopics:
        href: /design/guidelines/ausdto-api-design-guide/topics
    references:
      - name: Management state with HATEOAS
        url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
  - guideline_id: cisco-api-design-guide
    guideline_title: API Design Guide
    guideline_type: github
    guideline_url: 'https://github.com/CiscoDevNet/api-design-guide'
    guideline_company: Cisco
    guideline_companyLogoUrl: /media/logos/cisco.png
    guideline_companyUrl: 'http://developer.cisco.com/'
    guideline_screenshotUrl: /media/screenshots/cisco-api-design-guide.png
    guideline_date: 2015-08-21T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cisco-api-design-guide
      guidelineTopics:
        href: /design/guidelines/cisco-api-design-guide/topics
    references:
      - name: 3.3 Representations
        quote: 3.3.3 A resource identifier labeled "url" MUST be present in all RESTful API resource representations
        url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
  - guideline_id: cloud-foundy-cloud-controller-api-style-guide
    guideline_title: Cloud Controller API v3 Style Guide (Proposal)
    guideline_type: github
    guideline_url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
    guideline_company: Cloud Foundry
    guideline_companyLogoUrl: /media/logos/cloudfoundry.png
    guideline_companyUrl: 'https://www.cloudfoundry.org/'
    guideline_screenshotUrl: /media/screenshots/cloud-foundy-cloud-controller-api-style-guide.png
    guideline_date: 2016-05-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-18T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
      guidelineTopics:
        href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
    references:
      - name: Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
      - name: Links
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
      - name: Includind Related Resources
        url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
  - guideline_id: haufe-api-styleguide
    guideline_title: Haufe API style guide
    guideline_type: github
    guideline_url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
    guideline_company: Haufe
    guideline_companyLogoUrl: /media/logos/haufe.png
    guideline_companyUrl: 'http://dev.haufe.com/'
    guideline_screenshotUrl: /media/screenshots/haufe-api-styleguide.png
    guideline_date: 2015-01-15T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/haufe-api-styleguide
      guidelineTopics:
        href: /design/guidelines/haufe-api-styleguide/topics
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
  - guideline_id: paypal-api-style-guide
    guideline_title: API Style Guide
    guideline_type: github
    guideline_url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
    guideline_company: PayPal
    guideline_companyLogoUrl: /media/logos/paypal.png
    guideline_companyUrl: 'https://developer.paypal.com/'
    guideline_screenshotUrl: /media/screenshots/paypal-api-style-guide.png
    guideline_date: 2016-08-11T00:00:00.000Z
    guideline_reviewDate: 2016-08-31T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/paypal-api-style-guide
      guidelineTopics:
        href: /design/guidelines/paypal-api-style-guide/topics
    references:
      - name: Paging Hypermedia Links
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#hypermedia-links'
      - name: Create New Resource
        url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
        quote: Hypermedia links provide an easy way to get the URL of the newly created resource
  - guideline_id: redhat-thoughts-on-restful-api-design
    guideline_title: Thoughts on RESTful API Design
    guideline_type: website
    guideline_url: 'http://restful-api-design.readthedocs.io/en/latest/'
    guideline_company: Red Hat
    guideline_companyLogoUrl: /media/logos/redhat.png
    guideline_companyUrl: 'https://www.redhat.com/'
    guideline_screenshotUrl: /media/screenshots/redhat-thoughts-on-restful-api-design.png
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
      - name: REST Metadata
        url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
      - name: Link Headers
        url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
      - name: Relationships
        url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
  - guideline_id: zalando-restful-api-guidelines
    guideline_title: RESTFul API Guidelines
    guideline_type: website
    guideline_url: 'http://zalando.github.io/restful-api-guidelines/'
    guideline_company: Zalando
    guideline_companyLogoUrl: /media/logos/zalando.png
    guideline_companyUrl: 'https://tech.zalando.de/'
    guideline_screenshotUrl: /media/screenshots/zalando-restful-api-guidelines.png
    guideline_date: 2016-01-22T00:00:00.000Z
    guideline_reviewDate: 2016-08-28T00:00:00.000Z
    guideline__links:
      self:
        href: /design/guidelines/zalando-restful-api-guidelines
      guidelineTopics:
        href: /design/guidelines/zalando-restful-api-guidelines/topics
    references:
      - name: Use Pagination Links Where Applicable
        url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html#could-use-pagination-links-where-applicable'
      - name: Hypermedia
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html'
      - name: Use a well-defined subset of HAL
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
      - name: Do Not Use Link Headers with JSON entities
        url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
---