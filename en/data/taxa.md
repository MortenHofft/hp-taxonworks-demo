---
title: Taxa
description: Search taxa via the TaxonWorks API
permalink: /taxa/search
lang-ref: taxa
layout: compose
composition:
  - type: pageMarkdown
  - type: taxaSearch
    inlineData:
      apiUrl: https://sfg.taxonworks.org/api/v1
      # projectToken: your-project-token-here  # set this to a TaxonWorks project_token to enable results
      perPage: 25
---

# Taxa search

Search taxa via the TaxonWorks API. Configure the `apiUrl` and `projectToken`
for this block in [`en/data/taxa.md`](./taxa.md) frontmatter.
