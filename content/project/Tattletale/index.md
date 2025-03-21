---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tattletale"
summary: "Detecting and preventing inferences in the presence of data depencies"
authors: [nick]
tags: [Privacy, Inference Control, Access Control, Data Dependencies]
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

url_code: "https://github.com/DIPrLab/Tattle-Tale"
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


Tattletale uses denial constraints to discovery data inferences inside of a database relative to sensitive cells.  The cells that make up the denial constraints are then checked to see which cells infer information on them.  In the end all the cells that infer data on the sensitive cells and the cells that could be used to reconstruct those inferences are placed into a list which is used to generate a view that does not contain those cells.  Since inference can only be reconstructed as long as only one predicate is missing we can use that to minimize how many cells we have to hide.  The benefit of Tattletale is that it provides protection against inference which access control lists don't provide.  The current challenge is trying to improve the run time performance and decrease the number of cells that have to be hidden while also guaranteeing a certain level of protection against reconstruction.Tattletale uses denial constraints to discovery data inferences inside of a database relative to sensitive cells.  The cells that make up the denial constraints are then checked to see which cells infer information on them.  In the end all the cells that infer data on the sensitive cells and the cells that could be used to reconstruct those inferences are placed into a list which is used to generate a view that does not contain those cells.  Since inference can only be reconstructed as long as only one predicate is missing we can use that to minimize how many cells we have to hide.  The benefit of Tattletale is that it provides protection against inference which access control lists don't provide.  The current challenge is trying to improve the run time performance and decrease the number of cells that have to be hidden while also guaranteeing a certain level of protection against reconstruction.