---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Access Control in Vector Databases"
summary: "Implementation of Role Based Access control in Vector Databases"
authors: [Lakshmi]
tags:
  [Privacy, Inference Control, multi modal, Access Control, Unstructured Data]
categories: []
share: false
date: 2025-02-20

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

url_code: "https://github.com/DIPrLab/VectorDB-Pinecone"
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

Vector databases are particularly well-suited for similarity search using search algorithms like approximate nearest neighbor (ANN) search and they are used in development of Retrieval-Augmented Generation (RAG) systems, to reduce hallucinations in responses of AI systems. One significant challenge in using vector databases, especially in applications like RAG, is ensuring data privacy and security. For example, a clothing company that builds an AI chatbot that interacts with a vector database containing customer orders and product data could expose sensitive customer information without proper access restrictions. Incorporating Fine-Grained Access Control in vector databases is important for enforcing user preferences on data sharing and complying with privacy regulations. This project explores how to embed fine-grained access control within vector databases to ensure secure and privacy-compliant query answering.
