---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Accord"
summary: "Constraint-driven Mediation of Multi-user Conflicts in Cloud Services"
authors: [grace]
tags: [Privacy, Access Control, Cloud, Web Applications]
categories: []
share: false
date: 2024-06-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: https://github.com/DIPrLab/ACCORD
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Users are increasingly adopting collaborative cloud services like Google Drive.
The lack of fine-grained access controls on many cloud services make actions that violate the expectations of other users likely, resulting in multiuser conflicts.
For example, a user with editor permissions may add a user outside the organization and revoke the permissions of another user, all without consent from the original resource owner. 
These multiuser conflicts may compromise a resource's confidentiality, integrity, or availability, leading to a lack of trust in cloud services. 

ACCORD is a web application built on top of Google Drive which prevents and detects multiuser conflicts.
It employs a simulator to help users preemptively identify potential conflicts and
assist them in defining action constraints.
Then, using these action constraints, ACCORD can automatically detect future conflicts and suggest resolutions.

Currently, we are testing the scalability and practicality of ACCORD with larger numbers of users and resources.
