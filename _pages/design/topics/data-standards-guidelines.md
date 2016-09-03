---
layout: topic
title: Standards data
permalink: /design/topics/data-standards
sort: Data_Standards data
topic_id: data-standards
topic_category: Data
topic_name: Standards data
topic_description: 'Which standard use for values like languages, countries, currencies, ...'
guidelines:
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
      - name: Currency
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#currency'
        quote: 3-character ISO-4217
      - name: Country
        url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#country'
        quote: ISO 3166-1-alpha-2
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
      - name: 'Standards could be used for Language, Country and Currency'
        url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-standards-could-be-used-for-language-country-and-currency'
      - name: 'Use Standards for Country, Language and Currency Codes'
        url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-standards-for-country-language-and-currency-codes'
---