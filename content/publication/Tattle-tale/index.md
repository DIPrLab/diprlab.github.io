---
title: "Don't Be a Tattle-Tale: Preventing Leakages through Data Dependencies on Access Control Protected Data"
authors:
  - Primal Pappachan, Shufan Zhang, Xi He, Sharad Mehrotra
date: "2020-12-01"
share: false
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Tattle-Tale: Preventing Leakages through Data Dependencies on Access Control Protected Data"
publication_short: 'Don"t Be a Tattle-Tale'

abstract: We study the problem of answering queries when part of the data may be sensitive and should not be leaked to the querier. Simply restricting the computation to non-sensitive part of the data may leak sensitive data through inference based on data dependencies. While inference control from data dependencies during query processing has been studied in the literature, existing solution either detect and deny queries causing leakage, or use a weak security model that only protects against exact reconstruction of the sensitive data. In this paper, we adopt a stronger security model based on full deniability that prevents any information about sensitive data to be inferred from query answers.

# Summary. An optional shortened abstract.
summary: This paper discusses a stronger security model that minimally hides non-sensitive cells during query processing, thus preventing information leakages about sensitive data to be inferred from query answers.

tags:
  - Source Themes
featured: false

links:
  - name: Link
    url: https://www.vldb.org/pvldb/vol15/p2437-pappachan.pdf
url_pdf: https://www.vldb.org/pvldb/vol15/p2437-pappachan.pdf
url_code: https://github.com/zshufan/Tattle-Tale
url_dataset: "#"
#url_poster: '#'
url_project: "../project/tattletale"
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  []
  #- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
