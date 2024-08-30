---
title: Recommendations for machine learning-assisted directed evolution with limited data
keywords:
- protein engineering
- low N
- active learning
lang: en-US
date-meta: '2024-08-30'
author-meta:
- Anthony Gitter
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Recommendations for machine learning-assisted directed evolution with limited data" />
  <meta name="citation_title" content="Recommendations for machine learning-assisted directed evolution with limited data" />
  <meta property="og:title" content="Recommendations for machine learning-assisted directed evolution with limited data" />
  <meta property="twitter:title" content="Recommendations for machine learning-assisted directed evolution with limited data" />
  <meta name="dc.date" content="2024-08-30" />
  <meta name="citation_publication_date" content="2024-08-30" />
  <meta property="article:published_time" content="2024-08-30" />
  <meta name="dc.modified" content="2024-08-30T13:52:12+00:00" />
  <meta property="article:modified_time" content="2024-08-30T13:52:12+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Anthony Gitter" />
  <meta name="citation_author_institution" content="Department of Biostatistics and Medical Informatics, University of Wisconsin-Madison" />
  <meta name="citation_author_institution" content="Morgridge Institute for Research" />
  <meta name="citation_author_orcid" content="0000-0002-5324-9833" />
  <meta name="twitter:creator" content="@anthonygitter" />
  <link rel="canonical" href="https://gitter-lab.github.io/low-n-mlde-review/" />
  <meta property="og:url" content="https://gitter-lab.github.io/low-n-mlde-review/" />
  <meta property="twitter:url" content="https://gitter-lab.github.io/low-n-mlde-review/" />
  <meta name="citation_fulltext_html_url" content="https://gitter-lab.github.io/low-n-mlde-review/" />
  <meta name="citation_pdf_url" content="https://gitter-lab.github.io/low-n-mlde-review/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://gitter-lab.github.io/low-n-mlde-review/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://gitter-lab.github.io/low-n-mlde-review/v/f2c9c47c8919efe7ee775f4273ce035b54168856/" />
  <meta name="manubot_html_url_versioned" content="https://gitter-lab.github.io/low-n-mlde-review/v/f2c9c47c8919efe7ee775f4273ce035b54168856/" />
  <meta name="manubot_pdf_url_versioned" content="https://gitter-lab.github.io/low-n-mlde-review/v/f2c9c47c8919efe7ee775f4273ce035b54168856/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://gitter-lab.github.io/low-n-mlde-review/v/f2c9c47c8919efe7ee775f4273ce035b54168856/))
was automatically generated
from [gitter-lab/low-n-mlde-review@f2c9c47](https://github.com/gitter-lab/low-n-mlde-review/tree/f2c9c47c8919efe7ee775f4273ce035b54168856)
on August 30, 2024.
</em></small>



## Authors



+ **Anthony Gitter**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-5324-9833](https://orcid.org/0000-0002-5324-9833)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [agitter](https://github.com/agitter)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [anthonygitter](https://twitter.com/anthonygitter)
    <br>
  <small>
     Department of Biostatistics and Medical Informatics, University of Wisconsin-Madison; Morgridge Institute for Research
     · Funded by NSF 2226451
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/gitter-lab/low-n-mlde-review/issues)

:::


## Abstract {.page_break_before}

This manuscript is a community perspective about recommendations for protein engineering in the low N setting [@doi:10.1038/s41592-021-01100-y] where there is little experimental sequence-function data available.
It focuses on techniques guided by machine learning.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

